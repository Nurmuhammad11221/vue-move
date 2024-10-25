<template>
  <nav>
    <div class="nav__container">
        <div class="nav__left">
            <img class="nav__img" :src="require('@/assets/1.1.png')" alt="">


        </div>

        <div class="nav__right">
            <a class="nav__link" href="#">Box Office</a>
            <a class="nav__link" href="#">Media</a>
            <a class="nav__link" href="#">Society</a>
            <a class="nav__link" href="#">Ratings</a>
            <a class="nav__link" href="#">DVD & Blu-Ray</a>
        </div>

        
    </div>
  </nav>
</template>

<script>
export default {

}
</script>

<style>
    .nav__container{
        height: 80px;
        margin-left: 20px;
        width: 100%;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    .nav__left{
        width: 115px;
        height: 60px;

    }

    .nav__right{
        display: flex;
        gap: 20px;
        
    }

    .nav__link{
        color: black;
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        font-weight: 400;
        font-size: 16px;
        transition: 0.3s;
    }

    .nav__link:hover{
        color: white;
        background-color: #EA4737;
        width: 110px;
        height: 80px;
        text-align: center;
        align-content: center;
    }
</style>