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
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
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
                            <li><a href="#">Term Of Use</a></li>
                            <li><a href="#">Privacy policy(New)</a></li>
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPSC Certificates</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>
                    </div>
                    <div class="nav-col">
                        <h4>SITES</h4>
                        <ul>
                            <li><a href="#">DC</a></li>
                            <li><a href="#">MAD Magazine</a></li>
                            <li><a href="#">DC Kids</a></li>
                            <li><a href="#">DC Universe</a></li>
                            <li><a href="#">DC Power Visa</a></li>
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
<style lang="scss" scoped>
#top-footer {
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-position: bottom;
}

nav {
    width: 50%;

    .nav-row {
        display: flex;
        margin: 0 auto;

        .nav-col {
            flex-basis: calc(100% / 3);
            padding: 10px;
            display: flex;
            flex-direction: column;

            h4 {
                color: white;
                margin: 10px;
            }

            ul {
                display: flex;
                flex-direction: column;
                list-style: none;

                li a {
                    font-size: 12px;
                    text-decoration: none;
                    color: gray;
                    padding: 10px;
                }
            }
        }
    }
}



img {
    height: 400px;
}
</style>