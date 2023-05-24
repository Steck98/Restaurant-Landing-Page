<template>
    <div class="header">
        <div>
            <navigation />
            <h1>Indulge in Mexican culinary delights.</h1>
            <img class="header__main-decoration" src="../assets/img/tacos.png" alt="/" width="694" height="694">
            <img class="header__decoration header__decoration--left" src="../assets/img/line.png" alt="/" width="440" height="590">
            <img class="header__decoration header__decoration--right" src="../assets/img/line.png" alt="/" width="440" height="590">
        </div>
    </div>
</template>
<style lang="scss" scoped>
.header{
    height: 100%;
    background-color: $orange;
    position: relative;
    h1{
        padding-top: rem(100px);
        text-align: center;
        margin: 0 auto;
        max-width: 75%;
        text-transform: uppercase;
    }
    &__main-decoration{
        display: flex;
        padding-bottom: rem(64px);
        margin: 0 auto;
    }
    &__decoration{
        position: absolute;
        &--left{
            top: 0;
            left: 0;
            transform: rotate(180deg);
        }
        &--right{
            bottom: 0;
            right: 0;
        }
    }
    
}
</style>