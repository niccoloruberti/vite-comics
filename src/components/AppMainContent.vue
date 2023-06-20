<script>
export default {
    
}
</script>

<template>
    <div class="background">
        <div class="container">
            <span>Content goes here</span> 
        </div>
    </div>
</template>

<style scoped lang="scss">
    @use '../styles/generals.scss' as *;

    .background {
        width: 100%;
        background-color: black;

        .container {
            height: 100px;

            span {
                color: white;
            };
        }
    }
</style>