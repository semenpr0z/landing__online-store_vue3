<script setup>
    const props = defineProps({
        title: {
            type: String,
            required: false
        },
        description: {
            type: String,
            required: false
        },
        link: {
            type: String,
            required: false
        },
        colorTitle: {
            type: String,
            default: ''
        },
        colorDescription: {
            type: String,
            default: '#5B5676'
        },
        colorLink: {
            type: String,
            default: '#2A254B'
        },
        background: {
            type: String,
            default: '#fff'
        }
    })
</script>

<template>
    <div
    :style="{backgroundColor: background}"
    class="hero-info">
        <div class="hero-info-text">
            <h2
            :style="{color: colorTitle}"
            class="hero-info__title">{{ title }}</h2>
            <span
            :style="{color: colorDescription}"
            class="hero-info__description">{{ description }}</span>
        </div>
        <a
        :style="{color: colorLink}"
        :href="link"
        class="hero-info-link">View collection</a>
    </div>
</template>

<style lang="scss" scoped>
.hero{
    &-info{
        background: #FFFFFF;
        max-width: 630px;
        min-height: 444px;
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
            width: 170px;
            height: 56px;
            display: flex;
            justify-content: center;
            align-items: center;
            background: rgba(249, 249, 249, 0.15);
            &:hover{
                background: rgba(249, 249, 249, 0.30);
            }
        }
    }
}
</style>