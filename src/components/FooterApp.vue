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
            <div>
                <h2>DC COMICS</h2>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movie</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
                <h2>SHOP</h2>
                <ul>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>
            <div>
                <h2>DC</h2>
                <ul>
                    <li>Terms Of Use</li>
                    <li>Privacy policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Adverstising</li>
                    <li>Jobs</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
            </div>
            <div>
                <h2>SITES</h2>
                <ul>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>
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
.footer_info {
    position: relative;
    background-image: url('/img/footer-bg.jpg');
    background-size: cover;
    

    .container {
        padding: 50px;
        display: flex;
        gap: 30px;
        color: white;
    }

    ul {
        margin-top: 5px;
        margin-bottom: 15px;
        display: flex;
        flex-direction: column;
        li{
            padding: 7px 0;
            color: grey;
        }
    }

    .imgBg {
        display: flex;
        position: absolute;
        right: 350px;
        top: -50px;
        z-index: 1;
    }
}

.footer_profiles {
    position: relative;
    z-index: 2;
    background-color: #2D2A22;
    padding: 40px;

    .container {
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
}
</style>