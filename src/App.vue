<template>
  <div id="app">
    <myName name="Akinyemi Vek"/>
  </div>
</template>

<script>
import myName from './components/myName.vue'

export default {
  name: 'App',
  components: {
    myName
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #111111;
  color: #EEEEEE;
  margin: 0px;
  padding: 255px;
}
</style>
