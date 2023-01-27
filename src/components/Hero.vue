<script setup>
    import HeroInformation from './HeroInformation.vue';
</script>

<template>
    <div class="hero">
            <HeroInformation
            title="Luxury homeware for people who love timeless design quality"
            description="Shop the new Spring 2022 collection today"
            link="#"></HeroInformation>
    </div>
</template>

<style lang="scss" scoped>
.hero{
    background-image: url('/img/hero.jpg');
    height: 704px;
    background-size: cover;
    display: flex;
    align-items: center;
    justify-content: flex-end;
    padding-right: 80px;
        &-info__title{
            font-family: 'Clash Display';
            font-weight: 400;
            font-size: 32px;
            line-height: 45px;
            margin: 0 0 20px;
        }
        &-info__description{
            font-weight: 400;
            font-size: 18px;
            line-height: 27px;
            color: #5B5676;
        }
        &-info-link{
            color: #2A254B;
            text-decoration: none;
            &:hover{
                text-decoration: underline;
            }
        }
}
</style>