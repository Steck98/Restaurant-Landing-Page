<template>
    <div class="navigation">
        <div class="row navigation__wrapper">
            <div class="navigation__left-side">
                <p>Caliente</p>
            </div>
            <div class="navigation__right-side">
                <a href="#">Home</a>
                <a href="#">About</a>
                <a href="#">Menu </a>
                <a href="#">Contact</a>
                <button class="button">Order Now</button>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.navigation{
    padding-top: rem(32px);
&__left-side{
width: 50%;
}

&__right-side{
    width: 50%;
    display: flex;
    align-items: center;
    padding: 0px;
    gap: 36px;
    justify-content: flex-end;
}
.button{
    background-color: $font;
    color: #fff;
    padding: rem(12px) rem(16px);
}
}


</style>