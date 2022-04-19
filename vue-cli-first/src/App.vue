<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld/>
    <TitoloExe/>
    <HeroPage/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TitoloExe from './components/TitoloExe.vue'
import HeroPage from './components/HeroPage.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TitoloExe,
    HeroPage
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
