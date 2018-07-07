<template>
  <div id="app">
    <DeveloperTest msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import DeveloperTest from './components/DeveloperTest.vue'

export default {
  name: 'app',
  components: {
    DeveloperTest
  }
}
</script>

<style>
#app {
  text-align: center;
  font-family: Helvetica, Arial, sans-serif;
}

body {
  margin: 0;
}
</style>
