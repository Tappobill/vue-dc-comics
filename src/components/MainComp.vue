<template>
    <div>
        <div class="black">
            <div class="main-1">
                <p> Content goes here </p>
            </div>
        </div>

        <div class="blue">
            <div class="main-2">
                <div class="icon">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    DIGITAL COMICS
                </div>

                <div class="icon">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    DC MERCHANDISE
                </div>

                <div class="icon">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    SUBSCRIPTION
                </div>

                <div class="icon">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    COMIC SHOP LOCATOR
                </div>

                <div class="icon">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    DC POWER VISA
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'MainComp'
}
</script>

<style lang="scss" scoped>
@import "../assets/style/variabili.scss";
@import "../assets/style/mixin.scss";

* {
    @include reset($reset: 'standard');
}

.main-1{
    @include box80($box80: 'standard');
}
.main-2 {
    @include box80($box80: 'standard');
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 30px;
    color: white;
    font-size: 10px;
    margin-right: 20px;
}

.black {
    height: 100px;
    background-color: #262626;
    text-align: start;
    color: white;
    font-size: 20px;
    padding-top: 40px;
}

.blue {    
    background-color: #0C7CEC;
}

.icon{
    display: flex;
    align-items: center;
}

img{
    width: 15%;
    margin-right: 10px;
}
</style>