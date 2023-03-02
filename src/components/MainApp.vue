<script>
export default {
    data() {
        return {

        }
    }
}
</script>

<template>
    <section class="main_here">
        <h2>Content goes here</h2>
    </section>
    <section class="main_cards">
        <ul class="cards">
            <li>
                <a href="">
                    <img src="../../public/img/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </a>
            </li>
            <li>
                <a href="">
                    <img src="../../public/img/buy-comics-merchandise.png" alt="">
                    <span>DC MERCHANDISE</span>
                </a>
            </li>
            <li>
                <a href="">
                    <img src="../../public/img/buy-comics-subscriptions.png" alt="">
                    <span>SUBSCRIPTION</span>
                </a>
            </li>
            <li>
                <a href="">
                    <img src="../../public/img/buy-comics-shop-locator.png" alt="">
                    <span>COMIC SHOP LOCATOR</span>
                </a>
            </li>
            <li>
                <a href="">
                    <img src="../../public/img/buy-dc-power-visa.svg" alt="">
                    <span>DC POWER VISA</span>
                </a>
            </li>
        </ul>
    </section>
</template>

<style scoped>
.main_cards {
    background-color: #0077F8;
}

ul {
    display: flex;
    gap: 20px;
    list-style: none;
    align-items: center;
}

a {
    display: flex;
    align-items: center;
    color: white;
}

img {
    width: 50px;
}
</style>