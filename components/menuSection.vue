<template>
    <div class="menu">
        <div class="menu__title">
            <h2>Authentic Mexican Flavors: Our Menu</h2>
            <p>Our menu features fresh and high-quality ingredients, offering a <br /> wide variety of classic dishes that are sure to satisfy every palate.</p>
        </div>
        <div class="menu__content">
            <div class="menu__content-section">
                <img src="../assets/img/menu1.png" alt="/" height="350">
                <img src="../assets/img/menu2.png" alt="/"  height="350">
            </div>
            <div class="menu__content-section">
                <img src="../assets/img/menu3.png" alt="/"  height="350">
            </div>
            <div class="menu__content-section">
                <img src="../assets/img/menu4.png" alt="/"  height="350">
                <img src="../assets/img/menu5.png" alt="/"  height="350">
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.menu{
    background-color: $font;
    padding: 0 rem(64px) rem(124px) rem(64px);
    &__title{
        display: flex;
        text-align: center;
        justify-content: center;
        flex-direction: column;
        max-width: 60%;
        margin: 0 auto;
        h2{
            color: $orange;
            margin: rem(100px) 0 rem(24px) 0;
        }
        p{
            color: #fff;
            margin-bottom: rem(100px);
        }
    }
    &__content{
        display: flex;
        flex-direction: column;
        color: #fff;
    }
    &__content-section{
        overflow: hidden;
        width: 100%;
        height: rem(350px);
        img{
            height: 100%;
            object-fit: none;
            margin: rem(16px) 0;
            width: 100%;
        }
       
       
    }
    &__content-section:nth-child(1){
        display: flex;
        img:nth-child(1){
            width: 33%;
        }
    }
    &__content-section:nth-child(3){
        display: flex;
        img:nth-child(2){
            width: 33%;
        }
    }

}
</style>