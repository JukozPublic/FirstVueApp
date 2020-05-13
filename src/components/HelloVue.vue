<template>
  <div class="helloVue">
    <h1>{{ msg }}</h1>
  </div>
</template>
 
<script>
export default {
  name: "HelloVue",
  props: {
    msg: String
  }
};
</script>
 
<style>
</style>