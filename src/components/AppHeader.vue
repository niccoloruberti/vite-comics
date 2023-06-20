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
        <div class="logo">
            <img src="../assets/img/dc-logo.png">
        </div>
        <nav class="menu">
            <ul>
                <li v-for="(item, index) in menu" :key="index">{{ item.text }}</li>
            </ul>
        </nav>
    </header>
</template>

<style>
    
</style>