<script>
export default {
    props: {
        myCard: Object
    }
}
</script>

<template lang="">
    <div class="card">
        <img :src="myCard.thumb">
        <h3>{{ myCard.series}}</h3>
    </div>
</template>

<style scoped lang="scss">
    .card {
        width: calc(100% / 6 - 20px);
        margin: 20px 10px;
        display: flex;
        flex-direction: column;
        align-items: center;

        img {
            width: 100%;
            height: 250px;
            object-fit: fill;
        }

        h3 {
            color: white;
            text-transform: uppercase;
            font-size: 12px;
            margin-top: 10px;
        }
    }
</style>