<template>
  <div id="app">
    <HeadComp />
    <MainComp />
    <FootComp />
  </div>
</template>

<script>
import HeadComp from './components/HeadComp.vue'
import MainComp from './components/MainComp.vue'
import FootComp from './components/FootComp.vue'

export default {
  name: 'App',
  components: {
    HeadComp,
    MainComp,
    FootComp
  }
}
</script>

<style lang="scss">

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
