<script>
    export default{
        data(){
            return{
                
            }
        }
    }
</script>

<template>
    <section class="footer_info"></section>
    <section class="footer_profiles">
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
    </section>
</template>

<style scoped>
    .footer_profiles{
        background-color: #2D2A22;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    ul{
        display: flex;
        align-items: center;
        gap: 20px;
        list-style: none;
    }
    .follow{
        font-weight: bold;
        color: #0077F8;
    }
    .sing-up{
        padding: 10px;
        border: 2px solid #0077F8;
        color: white;
    }
</style>