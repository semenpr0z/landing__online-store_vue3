<template>
    <div class="hero">
        
        <div class="hero-info">
            <div class="hero-info-text">
                <h2 class="hero-info__title">Luxury homeware for people who love timeless design quality</h2>
                <span class="hero-info__description">Shop the new Spring 2022 collection today</span>
            </div>
            <a href="#" class="hero-info-link">View collection</a>
        </div>
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
    &-info{
        background: #FFFFFF;
        max-width: 630px;
        height: 444px;
        padding: 50px 55px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        &__title{
            font-family: 'Clash Display';
            font-weight: 400;
            font-size: 32px;
            line-height: 45px;
            margin: 0 0 20px;
        }
        &__description{
            font-weight: 400;
            font-size: 18px;
            line-height: 27px;
            color: #5B5676;
        }
        &-link{
            color: #2A254B;
            text-decoration: none;
            &:hover{
                text-decoration: underline;
            }
        }
    }
}
</style>