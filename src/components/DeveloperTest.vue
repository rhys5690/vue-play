<template>
  <div class='DeveloperTest'>
    <TopSection />
    <img src='../assets/beyond-valley.png' width='100%' alt='beyond valley'/>
  </div>
</template>

<script>
import TopSection from './TopSection.vue';
export default {
  name: 'DeveloperTest',
  components: {
    TopSection
  },
  props: {
    msg: String
  }
};
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
