<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TitleComponent test="La mia prima app con Vue CLI!"/>
    <HeroComponent/>
  </div>
</template>

<script>
import TitleComponent from "./components/TitleComponent.vue";
import HeroComponent from "./components/HeroComponent.vue";

export default {
  name: 'App',
  components: {
    TitleComponent,
    HeroComponent,
  }
}
</script>

<style lang="scss">
/* *RESET* */
*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;   
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
