<template>
    <header class="header">
        <div class="header-top">
            <div class="header-top-search">
                <img src="/svg/header-search.svg" alt="search">
            </div>
            <a href="#" class="header-logo">Avion</a>
            <div class="header-top-right">
                <div class="header-top-right__cart">
                    <a href="#">
                        <img src="/svg/header-cart.svg" alt="cart">
                    </a>
                </div>
                <div class="header-top-right__user">
                    <a href="#">
                        <img src="/svg/header-user.svg" alt="user">
                    </a>
                </div>
            </div>
        </div>
    </header>
</template>

<script setup>
    
</script>

<style lang="scss" scoped>
.header{
    background: #fff;
    height: 132px;
    &-top{
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        height: 70px;
        align-items: center;
        border-bottom: 1px solid rgba(0, 0, 0, 0.1);
        margin: 0 28px;

        &-right{
        display: flex;
        align-items: center;
        justify-content: flex-end;

        &__cart{
            margin-right: 16px;
        }
    }
    }
    &-logo{
        font-family: 'Clash Display', sans-serif;
        font-weight: 400;
        font-size: 24px;
        line-height: 30px;
        color: #22202E;
        text-decoration: none;
        text-align: center;
        &hover{
            text-decoration: underline;
        }
    }
}
</style>