<script>
export default {
    name: 'AppHeader',
    data: () => ({
        elements: [
            {
                text: 'Characters',
                url: '#',
                current: false,
            },
            {
                text: 'Comics',
                url: '#',
                current: true,
            },
            {
                text: 'Movies',
                url: '#',
                current: false,
            },
            {
                text: 'TV',
                url: '#',
                current: false,
            },
            {
                text: 'Games',
                url: '#',
                current: false,
            },
            {
                text: 'Collectibles',
                url: '#',
                current: false,
            },
            {
                text: 'Videos',
                url: '#',
                current: false,
            },
            {
                text: 'Fans',
                url: '#',
                current: false,
            },
            {
                text: 'News',
                url: '#',
                current: false,
            },
            {
                text: 'Shop',
                url: '#',
                current: false,
            },
        ],
    }),
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
                </ul>
            </nav>
        </div>
    </header>
</template>
<style lang="scss" scoped>
header {
    min-height: 150px;
    background-color: white;

    nav {
        ul {
            display: flex;
            list-style: none;

            li {
                padding: 65px 0;

                a {
                    font-size: 1rem;
                    padding: 10px;
                    text-decoration: none;
                    color: black;

                    &:hover {
                        color: #0282f9;
                        border-bottom: #0282f9 solid 2px;
                    }
                }
            }
        }
    }
}
</style>