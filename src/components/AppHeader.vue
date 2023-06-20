<script>
export default {
    data() {
        return {
            menu: [
                {
                    text: 'characters',
                    active: false
                },
                {
                    text: 'comics',
                    active: false
                },
                {
                    text: 'movies',
                    active: false
                },
                {
                    text: 'tv',
                    active: false
                },
                {
                    text: 'games',
                    active: false
                },
                {
                    text: 'collectibles',
                    active: false
                },
                {
                    text: 'videos',
                    active: false
                },
                {
                    text: 'fans',
                    active: false
                },
                {
                    text: 'news',
                    active: false
                },
                {
                    text: 'shop',
                    active: false
                },
            ]
        }
    },
}
</script>

<template>
    <header>
        <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png">
            </div>
            <nav class="menu">
                <ul>
                    <li v-for="(item, index) in menu" :key="index">{{ item.text }}</li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<style scoped lang="scss">
@use '../styles/partials/variables' as *;
@use '../styles/generals.scss' as *;

    header {
        width: 100%;
        background-color: #fff;
        .container {
            height: 100%;
            display: flex;
            justify-content: space-between;
            align-items: center;

            nav {
                width: 60%;
                height: 100%;

                ul {
                    padding: 0;
                    width: 100%;
                    height: 100%;
                    display: flex;
                    justify-content: space-around;
                    list-style: none;

                    li {
                        height: 100%;
                        text-transform: uppercase;
                        font-size: 12px;
                        font-weight: bold;

                            &:hover {
                                color: $color-primary;
                            }
                    }
                }
            }
        }
    }
</style>