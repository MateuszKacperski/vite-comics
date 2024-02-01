<script>
export default {
    name: 'AppHeader'
}
</script>
<template>
    <header>
        <figure>
            <img src="../assets/img/dc-logo.png" alt="DC logo">
        </figure>
        <nav>
            <ul>
                <li><a href="#">CHARACTERS</a></li>
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
    </header>
</template>
<style scope>
header {
    min-height: 150px;
    background-color: white;
    display: flex;
    justify-content: space-around;
    align-items: center;
}

nav ul {
    display: flex;
    list-style: none;

}

nav ul li a {
    padding: 60px 10px;
    text-decoration: none;
    color: black;
}
</style>