<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- HelloWorld msg="Welcome to Your Vue.js App"/ -->
  <MyFirstVueComponent></MyFirstVueComponent>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue';
import MyFirstVueComponent from './components/MyFirstVueComponent';

export default {
  name: 'App',
  components: {
    //HelloWorld,
    MyFirstVueComponent
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
