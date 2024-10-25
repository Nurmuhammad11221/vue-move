<template>
    <Nav />
    <Header />
</template>

<script>
import Header from './components/Header.vue';
import Nav from './components/Nav.vue';



export default {
    components: {
        Nav,
        Header
    }
}
</script>

<style>
* {
    padding: 0;
    margin: 0%;
    text-decoration: none;
}

</style>