<script>
    export default{
        data(){
            return{
                
            }
        }
    }
</script>

<template>
    <section class="header_list">
        <div class="logo">
            <img src="../../public/img/dc-logo.png" alt="">
        </div>
        <div class="list">
            <ul>
                <li><a href="">CHARACTES</a></li>
                <li><a href="">COMICS</a></li>
                <li><a href="">MOVIE</a></li>
                <li><a href="">TV</a></li>
                <li><a href="">GAME</a></li>
                <li><a href="">COLLECTIBLE</a></li>
                <li><a href="">VIDEOS</a></li>
                <li><a href="">FANS</a></li>
                <li><a href="">NEWS</a></li>
                <li><a href="">SHOP</a></li>
            </ul>
        </div>
    </section>
</template>

<style scoped>
    .header_list{
        display: flex;
        justify-content: space-between;
        align-items: center;
        background-color: white;
    }
    ul{
        display: flex;
        gap: 20px;
        list-style: none;
    }
    a{
        color: black;
    }
</style>