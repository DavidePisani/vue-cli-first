<template>
  <div id="app">
    <FirstAppCLI/>
    <MyHero/>

    <!-- <Hero Image="./assets/scimmia.jpg" > -->

  </div>
</template>

<script>
import FirstAppCLI from './components/FirstAppCLI.vue'
import MyHero from './components/MyHero.vue'

export default {
  name: 'App',
  components: {
    FirstAppCLI,
    MyHero
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
