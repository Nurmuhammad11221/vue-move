<template>
    <div class="header__container">
        <div class="header__img">
            <img class="header__img__move" :src="require('@/assets/1.2.png')" alt="">
            <img class="header__img__move" :src="require('@/assets/1.4.png')" alt="">
            <img class="header__img__move" :src="require('@/assets/1.6.png')" alt="">
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
    .header__img{
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>