<script setup>
    import Header from './components/layout/Header.vue';
    import Hero from './components/Hero.vue';
    import AboutBrand from './components/AboutBrand.vue';
    import Products from './components/Products4Column.vue';
    import Ideas from './components/Ideas.vue';
</script>

<template>
    <div class="container">
        <Header></Header>
        <Hero></Hero>
        <AboutBrand></AboutBrand>
        <Products></Products>
        <Ideas></Ideas>
    </div>
</template>

<style lang="scss">
@import url('https://fonts.cdnfonts.com/css/satoshi');
@import url('https://fonts.cdnfonts.com/css/clash-display');

* {
  box-sizing: border-box;
}

body{
    margin: 0;
    padding: 0;
    font-family: 'Satoshi', sans-serif;
    font-size: 16px;
    color: #22202E;
}

img{
    max-width: 100%;
}

.container{
    max-width: 1440px;
    margin: auto;
}
</style>