<template>
  <div class="checkbox-example">
    <input type="checkbox" v-model="checked">
    <label for="checkbox">{{ checked }}</label>    
  </div>
</template>

<script>
export default {
  name: "checkbox-example",
  data: () => ({
    checked: false
  })
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
