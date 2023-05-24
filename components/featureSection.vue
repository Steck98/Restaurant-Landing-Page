<template>
    <div class="featured">
        <div>
            
            <div>
                <h2 class="featured__title columns large-8 large-offset-2">These dishes are flying off the menu</h2>
                <div class="content columns large-8 large-offset-2">Looking for some culinary inspiration? These top-rated dishes are sure to delight your taste buds and satisfy your cravings.</div>
            </div>
            <div class="featured__card-wrapper">
                <div class="featured__card ">
                    <img class="featured__card-image" src="../assets/img/img1.png" alt="/" width="260" height="230">
                    <h4 class="featured__card-price">$8.50</h4>
                    <h4 class="featured__card-title">Spicy Beef Burrito</h4>
                    <button class="button">Order Now</button>
                </div>
                <div class="featured__card ">
                    <img class="featured__card-image" src="../assets/img/img4.png" alt="/" width="260" height="230">
                    <h4 class="featured__card-price">$7.00</h4>
                    <h4 class="featured__card-title">Chicken Quesadilla</h4>
                    <button class="button">Order Now</button>
                </div>
                <div class="featured__card ">
                    <img class="featured__card-image" src="../assets/img/img3.png" alt="/" width="260" height="230">
                    <h4 class="featured__card-price">$5.00</h4>
                    <h4 class="featured__card-title">Taco Supreme</h4>
                    <button class="button">Order Now</button>
                </div>
                <div class="featured__card ">
                    <img class="featured__card-image" src="../assets/img/img2.png" alt="/" width="260" height="230">
                    <h4 class="featured__card-price">$12.00</h4>
                    <h4 class="featured__card-title">Mexican Enchilada</h4>
                    <button class="button">Order Now</button>
                </div>
            </div>
        </div>
        <img class="featured__decoration" src="../assets/img/line.png" alt="/" width="440" height="590">
    </div>
</template>
<style lang="scss" scoped>
.featured{
    color: #fff;
    background-color: $font;
    display: flex;
    justify-content: center;
    height: 100%;
    position: relative;
    padding-bottom: rem(124px);
 &__title{
    padding-top: rem(62px);
    text-align: center;
    text-transform: uppercase;
    color: $orange;
 }
 &__decoration{
    position: absolute;
    bottom: 0;
    right: 0;
 }
 .content{
    text-align: center;
 }
 &__card-wrapper{
    display: flex;
    flex-direction: row; 
    flex-wrap: nowrap;
    align-items: flex-start;
    padding: 0px;
    gap: 20px;
    padding-top: rem(64px);
 }
 &__card{
    z-index: 1;
    background-color: $orange;
    height: 100%;
    padding: rem(24px) rem(25px);
    &-image{
        width: rem(260px);
        height: rem(230px);
    }
    &-price{
        color: #fff;
    }
 }
.button{
    background-color: $font;
    color: #fff;
    padding: rem(12px) rem(16px);
    
}
}
</style>