<template>
    <header>
        <div class="header container">
            <div class="logo">
                <img src="@/assets/dc-logo.png">
            </div>
            <ul>
                <li>characters</li>
                <li>comics</li>
                <li>movies</li>
                <li>tv</li>
                <li>games</li>
                <li>collectibles</li>
                <li>videos</li>
                <li>fans</li>
                <li>news</li>
                <li>shop</li>
            </ul>
        </div>
    </header>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';
header {

    .header {
        height: 100px;
        display: flex;
        justify-content: space-between;
        align-items: center;

        .logo {

            > img {
                width: 70%;
            }
        }

        ul {
            list-style: none;
            display: flex;

            li {
                text-transform: uppercase;
                margin: 10px;
                cursor: pointer;

                &:hover {
                    color: $text-primary-color;
                }
            }
        }
    }
}
</style>