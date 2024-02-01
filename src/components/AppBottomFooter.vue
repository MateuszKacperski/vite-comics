<script>
export default {
    name: 'AppBottomFooter'
}
</script>
<template>
    <section id="bottom-footer">
        <div class="container">
            <div>
                <button>SING-UP-NOW!</button>
            </div>
            <div class="right">
                <h3>FOLLOW US</h3>
                <img src="../assets/img/footer-facebook.png" alt="Facebook">
                <img src="../assets/img/footer-twitter.png" alt="Twitter">
                <img src="../assets/img/footer-youtube.png" alt="Youtube">
                <img src="../assets/img/footer-pinterest.png" alt="Printerest">
                <img src="../assets/img/footer-periscope.png" alt="Periscope">
            </div>
        </div>
    </section>
</template>
<style scoped>
#bottom-footer {
    background-color: #303030;
    min-height: 100px;
}

button {
    color: white;
    background-color: #303030;
    border: solid 2px #0282f9;
    padding: 10px;
}

.right {
    display: flex;
    align-items: center;
    justify-content: center;
}

.right img {
    padding: 10px;
}

h3 {
    color: #0282f9;
}
</style>