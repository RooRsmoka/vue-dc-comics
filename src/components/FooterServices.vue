<template>
    <div class="background">
        <div class="container">
            <div class="services">
                <div class="services-item">
                    <img src="@/assets/buy-comics-digital-comics.png" alt="">
                    <p>DIGITAL COMICS</p>
                </div>
                <div class="services-item">
                    <img src="@/assets/buy-comics-merchandise.png" alt="">
                    <p>DC MERCHANDISE</p>
                </div>
                <div class="services-item">
                    <img src="@/assets/buy-comics-subscriptions.png" alt="">
                    <p>SUBSCRIPTION</p>
                </div>
                <div class="services-item">
                    <img src="@/assets/buy-comics-shop-locator.png" alt="">
                    <p>COMIC SHOP LOCATOR</p>
                </div>
                <div class="services-item">
                    <img src="@/assets/buy-dc-power-visa.svg" alt="">
                    <p>DC POWER VISA</p>
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
    background-color: $text-primary-color;

    .services {
        padding: 30px 0;
        display: flex;
        justify-content: space-between;

        .services-item {
            height: 100px;
            display: flex;
            align-items: center;

            img {
                height: 50%;
            }

            p {
                padding: 0 20px;
                color: $text-secondary-color;
            }
        }
    }
}
</style>