<template>
    <header>
        <div class="container">
            <div class="header">
                <div class="logo">
                    <img src="@/assets/dc-logo.png">
                </div>
                <div class="nav-bar">
                    <ul>
                        <li v-for="link in nav" :key="link.id">
                            <a :href="link.url">
                                {{link.label}}
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    props: {
        nav: Array
    }
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
                text-transform: uppercase;
                margin: 10px;

                a {
                    text-decoration: none;
                    color: #464646;
                    font-weight: bold;
                    cursor: pointer;

                    &:hover {
                        color: $text-primary-color;
                    }
                }
            }
        }
    }
}
</style>