<template>
    <div class="founder">
        <img class="founder__decoration" src="../assets/img/line.png" alt="/" width="440" height="590">
        <div class="founder__image-wrapper">
            <img src="../assets/img/man.png" alt="founder">
        </div>
        <div class="founder__content-wrapper">
            <h2 class="founder__title">Our Founder's Legacy:</h2>
            <h4 class="h4--bold  founder__subtitle">A Passion for Authentic Mexican Cuisine</h4>
            <p>Jorge, the founder of our restaurant, grew up in a small village in Mexico where his mother ran a small street food stand. From a young age, he was fascinated by the aromas and flavors of the food she cooked and he developed a passion for cooking that stayed with him throughout his life. </p>
            <p>After years of perfecting his skills, Jorge decided to open his own restaurant in the heart of his hometown, where he could share his love of traditional Mexican cuisine with the world. </p>
            <p>With hard work, dedication, and a commitment to using only the freshest ingredients, his restaurant quickly became a beloved gathering place for locals and tourists alike. </p>
            <p>Today, we continue to honor Jorge's legacy by serving authentic and delicious Mexican dishes that are sure to satisfy your cravings and transport your taste buds to the heart of Mexico.</p>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.founder{
    background-color: $orange;
    position: relative;
    display: flex;
    justify-content: center;
    padding-bottom: rem(180px);
    &__subtitle{
        text-transform: uppercase;
        text-align: center;
    }

    &__title{
        text-align: center;
        letter-spacing: 0;
    }

    &__decoration{
        position: absolute;
        bottom: 0;
        left: 0;
        transform: scaleX(-1)
        
    }

    &__image-wrapper{

        max-width: 50%;
    }

    &__content-wrapper{
        max-width: 50%;
        padding: 0 rem(63px);
    }
    p{
        color: #fff;
        text-align: center;
        line-height: rem(32px);
        font-weight: 400;
    }
}
</style>