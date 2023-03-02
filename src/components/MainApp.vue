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
        <div class="container content">
            <h2>Content goes here</h2>
        </div>
    </section>
    <section class=" main_cards">
        <ul class="container cards">
            <li>
                <a href="">
                    <img src="/img/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </a>
            </li>
            <li>
                <a href="">
                    <img src="/img/buy-comics-merchandise.png" alt="">
                    <span>DC MERCHANDISE</span>
                </a>
            </li>
            <li>
                <a href="">
                    <img src="/img/buy-comics-subscriptions.png" alt="">
                    <span>SUBSCRIPTION</span>
                </a>
            </li>
            <li>
                <a href="">
                    <img  src="/img/buy-comics-shop-locator.png" alt="" class="img">
                    <span>COMIC SHOP LOCATOR</span>
                </a>
            </li>
            <li>
                <a href="">
                    <img src="/img/buy-dc-power-visa.svg" alt="">
                    <span>DC POWER VISA</span>
                </a>
            </li>
        </ul>
    </section>
</template>

<style lang="scss" scoped>
.main_here{
    background-color: black;
    color: white;
    padding: 50px;
    
}
.main_cards {
    padding: 30px;
    background-color: #0077F8;
}

ul {
    display: flex;
    gap: 80px;
    justify-content: center;
    align-items: center;
    list-style: none;
}

a {
    display: flex;
    align-items: center;
    gap: 10px;
    color: white;
}

img {
    width: 50px;
}
.img{
    width: 30px;
}
</style>