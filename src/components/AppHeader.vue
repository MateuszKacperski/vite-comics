<script>
export default {
    name: 'AppHeader'
}
</script>
<template>
    <header>
        <div class="container">

            <figure>
                <img src="../assets/img/dc-logo.png" alt="DC logo">
            </figure>
            <nav>
                <ul>
                    <li v-for="element in elements" :key="element.text"><a href="#">{{ element.text }}</a></li>
                    <li><a href="#">COMICS</a></li>
                    <li><a href="#">MOVIES</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">GAMES</a></li>
                    <li><a href="#">COLECTIONABLES</a></li>
                    <li><a href="#">VIDEOS</a></li>
                    <li><a href="#">FANS</a></li>
                    <li><a href="#">NEWS</a></li>
                    <li><a href="#">SHOP</a></li>
                </ul>
            </nav>
        </div>
    </header>
</template>
<style scoped>
header {
    min-height: 150px;
    background-color: white;
}

nav ul {
    display: flex;
    list-style: none;

}

nav ul li a {
    font-size: 1rem;
    padding: 60px 10px;
    text-decoration: none;
    color: black;
}
</style>