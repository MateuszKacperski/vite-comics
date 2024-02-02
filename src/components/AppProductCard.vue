<script>
export default {
    name: 'AppProductCard',
    props: {
        img: String,
        title: String
    }

}
</script>
<template>
    <div class="product-card">
        <div class="card-conteiner">
            <img :src="img" :alt="title">
            <h4>{{ title }}</h4>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.product-card {
    padding: 20px;


    img {
        display: block;
    }
}
</style>