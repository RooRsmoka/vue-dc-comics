<template>
    <header>
        <div class="container">
            <div class="header">
                <div class="logo">
                    <img src="@/assets/dc-logo.png">
                </div>
                <div class="nav-bar">
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
            </div>
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
    padding: 20px 0;

    .header {
        display: flex;
        justify-content: space-between;
        align-items: center;

        .logo {
            width: 100px;

            > img {
                width: 75%;
                cursor: pointer;
            }
        }

        ul {
            list-style: none;
            display: flex;

            li {
                color: #464646;
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