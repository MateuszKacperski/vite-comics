<script>
export default {
    name: 'AppTopFooter'
}
</script>
<template>
    <section id="top-footer">
        <div class="container">

            <nav>
                <div class="nav-row">
                    <div class="nav-col">
                        <h4>DC COMICS</h4>
                        <ul>
                            <li><a href="#">CHARACTERS</a></li>
                            <li><a href="#">COMICS</a></li>
                            <li><a href="#">MOVIES</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">GAMES</a></li>
                            <li><a href="#">VIDEOS</a></li>
                            <li><a href="#">FANS</a></li>
                            <li><a href="#">NEWS</a></li>
                        </ul>
                        <h4>SHOP</h4>
                        <ul>
                            <li><a href="#">ShopDC</a></li>
                            <li><a href="#">ShopDC Collectionables</a></li>
                        </ul>
                    </div>
                    <div class="nav-col">
                        <h4>DC</h4>
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
                        </ul>
                    </div>
                    <div class="nav-col">
                        <h4>SITES</h4>
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
                        </ul>
                    </div>
                </div>
            </nav>
            <div>
                <img src="../assets/img/dc-logo-bg.png" alt="DC logo">
            </div>
        </div>
    </section>
</template>
<style scoped>
#top-footer {
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-position: bottom;
}

nav {
    width: 50%;
}

.nav-row {
    display: flex;
    margin: 0 auto;
}

.nav-col {
    flex-basis: calc(100% / 3);
    padding: 10px;
    display: flex;
    flex-direction: column;
}

h4 {
    color: white;
    margin: 10px;
}

nav ul {
    display: flex;
    flex-direction: column;
    list-style: none;

}

nav ul li a {
    font-size: 12px;
    text-decoration: none;
    color: gray;
    padding: 10px;
}

img {
    height: 400px;
}
</style>