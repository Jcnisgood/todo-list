<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="toDoList"/>
    <BaseLayout />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import BaseLayout from './Layout/BaseLayout.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    BaseLayout
  }
}
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
