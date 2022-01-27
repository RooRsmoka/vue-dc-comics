<template>
    <div class="background">
        <div class="container">
            <div class="footer-container">
                <div class="footer-list">
                    <div class="list">
                        <p class="list-title">dc comics</p> 
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                    </div>
                    <div class="list">
                        <p class="list-title">shop</p> 
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </div>
                    <div class="list">
                        <p class="list-title">dc</p> 
                        <ul>
                            <li><a href="#">Terms Of Use</a></li>
                            <li><a href="#">Privacy Policy (New)</a></li>
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPSC Certificates</a></li>
                            <li><a href="#">Rating</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>
                    </div>
                    <div class="list">
                        <p class="list-title">sites</p> 
                        <ul>
                            <li><a href="#">DC</a></li>
                            <li><a href="#">MAD Magazine</a></li>
                            <li><a href="#">DC Kids</a></li>
                            <li><a href="#">DC Universe</a></li>
                            <li><a href="#">DC Power Visa</a></li>
                        </ul>
                    </div>
                </div>
                <div class="footer-logo">
                    <img src="@/assets/dc-logo-bg.png">
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
    background: url('../assets/footer-bg.jpg') center;
    background-size: cover;

    .footer-container {
        display: flex;
        justify-content: space-between;

        .footer-list {
            height: 500px;
            padding: 40px 0;
            display: flex;
            flex-direction: column;
            flex-wrap: wrap;

            .list {
                margin-right: 35px;
                margin-bottom: 20px;

                .list-title {
                    color: $text-secondary-color;
                    font-size: 22px;
                    text-transform: uppercase;
                    margin-bottom: 15px;
                }

                ul {
                    list-style: none;
                
                
                    li {
                        padding: 5px 0;
                    
                        a{
                            font-size: 16px;
                            color: #959595;
                            text-decoration: none;
                            cursor: pointer;

                            &:hover {
                                color: $text-secondary-color;
                            }
                        }
                    }
                }
            }  
        }

        .footer-logo {
            height: 500px;
            
            img {
                height: 100%;
            }
        }
    }
}

</style>