<script setup>
    import HeroInformation from './HeroInformation.vue';
</script>

<template>
    <div class="ideas">
        <HeroInformation
        title="It started with a small idea"
        description="A global brand with local beginnings, our story begain in a small studio in South London in early 2014"
        link="#"
        background="#2A254B"
        colorTitle="#FFFFFF"
        colorDescription="#FFFFFF"
        colorLink="#FFFFFF"></HeroInformation>
        <img src="img/room.jpg" alt="">
    </div>
</template>

<style lang="scss" scoped>
.ideas{
    padding: 0 80px;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    column-gap: 16px;
    margin-bottom: 60px;
}
</style>