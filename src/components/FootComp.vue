<template>
    <div>
        <div class="foot">
            <div class="foot-1">
                <div class="liste-foot">
                    <div class="comics-shop">
                        <div class="div-lista">
                           <span class="title">DC COMICS</span>
                            <ul>
                                <li>Characters</li>
                                <li>Comics</li>
                                <li>Movies</li>
                                <li>Tv</li>
                                <li>Games</li>
                                <li>Videos</li>
                                <li>News</li>
                            </ul>
                        </div>
                        <div class="div-lista">
                           <span class="title">SHOP</span>
                            <ul>
                                <li>Shop DC</li>
                                <li>Shop DC Collectbles</li>
                            </ul>
                        </div>
                    </div>
                    <div class="div-lista">
                        <span class="title">DC</span>
                        <ul>
                            <li>Terms Of Use</li>
                            <li>Privacy policy (New)</li>
                            <li>Ad Choices</li>
                            <li>Advertising</li>
                            <li>Jobs</li>
                            <li>Subscriptions</li>
                            <li>Talent Workshops</li>
                            <li>CPSC Certificates</li>
                            <li>Ratings</li>
                            <li>Shop Help</li>
                            <li>Contact Us</li>
                        </ul>
                    </div>
                    <div class="div-lista">
                        <span class="title">SITES</span>
                        <ul>
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>DC Kids</li>
                            <li>DC Universe</li>
                            <li>DC Power Visa</li>
                        </ul>
                    </div>
                </div>

                <div class="img-dc-padre">
                    <div class="img-dc">

                    </div>
                </div>
            </div>
        </div>

        <div>

        </div>
    </div>
</template>

<script>
    export default {
        name: 'FootComp'
    }
</script>

<style lang="scss" scoped>
@import "../assets/style/variabili.scss";
@import "../assets/style/mixin.scss";

* {
    @include reset($reset: 'standard');
}

.foot{    
    background-image: url(../assets/img/footer-bg.jpg);
    text-align: start;
    color: white;
    background-repeat: no-repeat;
    background-size: cover;       
}

.foot-1{
    @include box80($box80: 'standard');
    display: flex;
}

.liste-foot{
    display: flex;
    padding-bottom: 50px;
}

.div-lista{
    padding-top: 50px;
    margin-right: 50px;
}

.title{
    font-weight: bold;
    font-size: 18px;
}

ul{
    margin-top: 15px;
}

li{
    color: gray;
    margin-bottom: 5px;
}

.img-dc{
    background-image: url(../assets/img/dc-logo-bg.png);
    height: 100%;
    background-position: center;
    background-repeat: no-repeat;
}

.img-dc-padre{
    width: 80%;
}

</style>