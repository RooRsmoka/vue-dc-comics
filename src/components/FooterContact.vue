<template>
    <div class="background">
        <div class="container">
            <div class="contact">
                <div class="sign-up-btn">
                    sign-up now!
                </div>
                <div class="social">
                    <p>follow us</p>
                    <a href="#">
                        <img src="@/assets/footer-facebook.png" alt="Facebook">
                    </a>
                    <a href="">
                        <img src="@/assets/footer-twitter.png" alt="Twitter">
                    </a>
                    <a href="">
                        <img src="@/assets/footer-youtube.png" alt="Youtube">
                    </a>
                    <a href="">
                        <img src="@/assets/footer-pinterest.png" alt="Pinterest">
                    </a>
                    <a href="">
                        <img src="@/assets/footer-periscope.png" alt="Periscope">
                    </a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';
.background {
    background-color: #303030;

    .contact {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 20px 0;
    }

    .sign-up-btn {
        text-transform: uppercase;
        color: $text-secondary-color;
        padding: 10px;
        border: 2px $text-primary-color solid;
        cursor: pointer;

        &:hover {
            background-color: $text-primary-color;
        }
    }

    .social {
        display: flex;
        align-items: center;

        p {
            text-transform: uppercase;
            margin-right: 10px;
            font-weight: bold;
            color: $text-primary-color;
        }

        a {
            
            img {
                margin: 0 15px;
                cursor: pointer;
            }
        }
    }
}
</style>