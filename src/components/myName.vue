<template>
  <div>
    <h1> Hi, my name is <strong>{{ name }}</strong>.</h1>
  </div>
</template>

<script>
export default {
  props: [
    'name'
  ]
} 
</script>

