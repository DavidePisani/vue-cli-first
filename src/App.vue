<template>
  <div id="app">
    <FirstAppCLI msg="La mia prima app con Vue CLI!"/>

    <img alt="Vue logo" src="./assets/scimmia.jpg"> 
  </div>
</template>

<script>
import FirstAppCLI from './components/FirstAppCLI.vue'

export default {
  name: 'App',
  components: {
    FirstAppCLI
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
