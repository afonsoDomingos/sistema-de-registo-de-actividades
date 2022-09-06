<template>
<!--  <img alt="Vue logo" src="./assets/logo.png">-->
  <HomePrincipal msg="Welcome to Your Vue.js App"/>
  <about></about>
</template>

<script>
import HomePrincipal from './components/home.vue'
import About from "@/components/about";

export default {
  name: 'App',
  components: {
    About,
    HomePrincipal
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
