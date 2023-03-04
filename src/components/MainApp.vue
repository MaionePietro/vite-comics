<script>
export default {
    data() {
        return {
            comics: [
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/ACTIONCOMICS_Cv1045_04511_DIGITAL_62c87a85000af0.96479310.jpg?w=640",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/AMVAMP1976%2520%2528COVER%2529_6179b409d52e93.54241046.jpg?w=640",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/LR23282_AQM_01_300-001_HD_5f5b0c366be020.34549548.jpg?w=640",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/batgirl_v5_3_5b23e207ae1da9.74079044.jpg?w=640",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/BM_Cv118_11811_DIGITAL_61a919e4c95ab0.66239812.jpg?w=640",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/BM_Cv118_11811_DIGITAL_61a919e4c95ab0.66239812.jpg?w=640",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/1327_400x600.jpg?w=400",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/BMSM_08_300-001_HD_5e67cb816edbe5.46274351.jpg?w=640",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/sites/default/files/imce/2020/06-JUN/batman_thejoker_warzone_001_5ee278f0419c30.15413222.jpg",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/cover-v2_5f40314645a734.37285065.png?w=485",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/BMWK_HQ%2520%2528COVER%2529_60ca8a6db3da64.48239084.jpg?w=640",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/CTW_30_CVR_606ba780ba7df6.37255050.jpg?w=640",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel"
                }
            ]
        }
    }
}
</script>

<template>
    <section class="main_here">
        <div class="container grid-container">
            <div v-for="(comic, i) in comics"
            class="card">
                <div>
                    <img :src="comic.thumb" alt="">
                </div>
                <span class="tex">{{ comic.series }}</span>
            </div>
            
            
        </div>
    </section>


    <section class="main_cards">
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
                    <img src="/img/buy-comics-shop-locator.png" alt="" class="img">
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
.main_here {
    background-color: black;
    color: white;
    padding: 50px;

    .grid-container {
        display: grid;
        grid-template-columns: repeat(6, 1fr);
        gap: 10px;
        
        img{
            width: 100%;
            object-fit: cover; /* aggiunto */
            object-position: center; /* aggiunto */
        }
        .col {
            flex-grow: 1;
            flex-basis: 30%;
        }


        .card {
            padding: 20px;

            .card__title {
                font-size: 18px;
            }
        }
    }
}

.main_cards {
    padding: 30px;
    background-color: #0077F8;
    position: relative;
    z-index: 2;
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

.img {
    width: 30px;
}
</style>