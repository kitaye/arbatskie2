<template>
  <h1>Привет, я {{text}}</h1>
</template>
<script>
  export default {
    name: 'HelloWorld',
    props: ['text'],
  }
</script>
<style scoped>
  h1 {
    color: red;
  }
</style>
