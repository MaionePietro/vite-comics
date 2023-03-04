<script>
export default {
    data() {
        return {

        }
    }
}
</script>

<template>
    <section class="footer_info">
        <img src="/img/dc-logo-bg.png" alt="" class="imgBg">
        <div class="container">
            <ul>
                DC COMICS
                <li>a</li>
                <li>a</li>
                <li>a</li>
                <li>a</li>
                <li>a</li>
                <li>a</li>
                <li>a</li>
            </ul>
            <ul></ul>
            <ul></ul>
            <ul></ul>
        </div>
    </section>
    <section class="footer_profiles">
        <div class="container">
            <div>
                <a href="" class="sing-up">SING-UP NOW!</a>
            </div>
            <div>
                <ul>
                    <li><a class="follow" href="">FOLLOW US</a></li>
                    <li><a href=""><img src="../../public/img/footer-facebook.png" alt=""></a></li>
                    <li><a href=""><img src="../../public/img/footer-twitter.png" alt=""></a></li>
                    <li><a href=""><img src="../../public/img/footer-pinterest.png" alt=""></a></li>
                    <li><a href=""><img src="../../public/img/footer-youtube.png" alt=""></a></li>
                    <li><a href=""><img src="../../public/img/footer-twitter.png" alt=""></a></li>
                </ul>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>

.footer_info{
    position: relative;
    background-image: url('/img/footer-bg.jpg');
    background-size: cover;
    height: 400px;

    ul{
        color: white;
        display: flex;
        flex-direction: column;
    }
    .imgBg{
        display: flex;
        position: absolute;
        right: 350px;
        top: -80px;
        z-index: 1;
    }
}

.footer_profiles {
    position: relative;
    z-index: 2;
    background-color: #2D2A22;
    padding: 40px;
    .container{
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    ul {
    display: flex;
    align-items: center;
    gap: 20px;
    list-style: none;
}
}


.follow {
    font-weight: bold;
    color: #0077F8;
}

.sing-up {
    padding: 10px;
    border: 2px solid #0077F8;
    color: white;
}</style>