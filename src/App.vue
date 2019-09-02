<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <BootstrapContainer/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import BootstrapContainer from './components/BootstrapContainer';

export default {
  name: 'app',
  components: {
    HelloWorld,
    BootstrapContainer
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
