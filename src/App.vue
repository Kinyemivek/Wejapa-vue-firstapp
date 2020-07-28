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
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
  *,
  ::before,
  ::after {
    background-color: #111111;
    color: #EEEEEE;
  }

</style>
