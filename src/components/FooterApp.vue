<script>
import ListLink from './ListLink.vue';

export default {
    components:{
        ListLink
    },
    data() {
        return {
            links:[
                {
                    title: "DC COMICS",
                    urls: [
                        'Characters',
                        'Comics',
                        'Movie',
                        'TV',
                        'Games',
                        'Videos',
                        'News'
                    ]
                },
                {
                    title: "SHOP",
                    urls: [
                        'Shop DC',
                        'Shop DC Collectibles'
                    ]
                },
                {
                    title: "DC",
                    urls: [
                        'Terms Of Use',
                        'Privacy policy (New)',
                        'Ad Choices',
                        'Adverstising',
                        'Jobs',
                        'Talent Workshops',
                        'CPSC Certificates',
                        'Ratings',
                        'Shop Help',
                        'Contact Us'
                    ]
                },
                {
                    title: "SITES",
                    urls: [
                        'DC',
                        'MAD Magazine',
                        'DC Kids',
                        'DC Universe',
                        'DC Power Visa'
                    ]
                }
            ]
        }
    }
}
</script>

<template>
    <section class="footer_info">
        <img src="/img/dc-logo-bg.png" alt="" class="imgBg">
        <div class="container">
            <div>
                <ListLink :title="links[0].title" :urls="links[0].urls" />
                <ListLink :title="links[1].title" :urls="links[1].urls" />
            </div>
            <div>
                <ListLink :title="links[2].title" :urls="links[2].urls" />
            </div>
            <div>
                <ListLink :title="links[3].title" :urls="links[3].urls" />
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