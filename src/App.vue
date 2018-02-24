<template>
  <div id="app">
    <HelloWorld/>
    <SiblingVue/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import SiblingVue from './components/SiblingVue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    SiblingVue,
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
