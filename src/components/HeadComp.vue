<template>
    <div class="header">

        <div class="logo-head">
            <img src="../assets/img/dc-logo.png" alt="Logo DC">
        </div>

        <div class="lista-head">
            <ul>
                <li>
                    <a href="#">CHARACTERS</a>
                </li>
                <li>
                    <a href="#">COMICS</a>
                </li>
                <li>
                    <a href="#">MOVIES</a>
                </li>
                <li>
                    <a href="#">TV</a>
                </li>
                <li>
                    <a href="#">GAMES</a>
                </li>
                <li>
                    <a href="#">COLLECTIBLES</a>
                </li>
                <li>
                    <a href="#">VIDEOS</a>
                </li>
                <li>
                    <a href="#">FANS</a>
                </li>
                <li>
                    <a href="#">NEWS</a>
                </li>
                <li>
                    <a href="#">SHOP</a>
                </li>
            </ul>
        </div>

    </div>
</template>

<script>
export default {
    name: 'HeadComp'
}
</script>

<style lang="scss" scoped>
@import "../assets/style/variabili.scss";
@import "../assets/style/mixin.scss";

* {
   @include reset($reset:'standard');
}

.logo-head{
    padding-bottom: 30px;
}

.header {
    @include box80($box80: 'standard');
    display: flex;
    justify-content: space-between;
}

ul {
    display: flex;
    margin-top: 35px;

    li {
        margin: $margin;
        padding: $pad;
        font-size: 10px;

        a {
            text-decoration: none;
            color: black;
            font-weight: bold;
        }
    }    
}

a:hover{
    color: cornflowerblue;
    cursor: pointer;
    padding-bottom: 75.5px;
    border-bottom: 5px solid #0C7CEC;
}
</style>