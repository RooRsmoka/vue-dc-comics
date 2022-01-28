<template>
    <main>
        <div class="container">
            <div class="comics-list">
                <div class="comic-card" v-for="comic in comics" :key="comic.id">
                    <div class="comic-thumbnail">
                        <img :src="comic.thumb">
                    </div>
                    <p>{{comic.series}}</p>
                </div>
            </div>
            <div class="btn-box">
                <div class="more-btn">
                    Load more
                </div>
            </div>
        </div>
    </main>
</template>

<script>
export default {
    props: {
        comics: Array
    }
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';
main {
    background-color: #1C1C1C;
    padding: 50px 0;

    .comics-list {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;


        .comic-card {
            width: calc(1200px / 6);
            margin-bottom: 30px;

            .comic-thumbnail {
                width: 100%;

                img {
                }
            }

            p {
                font-size: 15px;
                margin: 15px 0;
                text-transform: uppercase;
                color: $text-secondary-color;
            }
        }  
    }

    .btn-box {
        display: flex;
        justify-content: center;

        .more-btn {
            background-color: $text-primary-color;
            color: $text-secondary-color;
            font-size: 15px;
            text-align: center;
            text-transform: uppercase;
            padding: 10px 50px;
            cursor: pointer;
        }
    }  
}
</style>