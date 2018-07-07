<template>
  <div class='TopSection'>
    <p class='TopSection__top-heading'>Brightness & Contrast Developer Test</p>
    <p class='TopSection__sub-heading'>01 Jun. 2018 - 31 Dec, 2019</p>
  </div>
</template>

<script>
export default {
  name: 'TopSection',
  props: {
  }
};
</script>

<style scoped>
.TopSection {
  background-color: #7344C0;
  padding: 20px;
}

.TopSection__top-heading, .TopSection__sub-heading {
  color: white;
  margin-bottom: 0;
  margin-top: 0;
}

.TopSection__top-heading {
  font-size: 15px;
  margin-bottom: 5px;
}

.TopSection__sub-heading {
  font-size: 13px;
}

</style>
