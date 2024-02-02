<script>
import AppProductCard from './AppProductCard.vue'
export default {
    name: 'AppMain',
    props: {
        comics: Array
    },
    components: {
        AppProductCard
    }
}
</script>
<template>
    <main class="container">
        <section id="products">
            <div class="card">
                <AppProductCard v-for="(comic, i) in comics" :key="i" :img="comic.thumb" :title="comic.series" />
            </div>
        </section>
    </main>
</template>
<style lang="scss" scoped>
main {
    color: white;
    min-height: 150px;

    .card {
        display: flex;
        flex-wrap: wrap;
        margin-top: 50px;

        .product-card {
            flex-basis: calc(100% / 6);
        }
    }
}
</style>