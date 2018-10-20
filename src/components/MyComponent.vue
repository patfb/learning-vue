<template>
  <div class="mycomponent">
    <h1>{{ greeting }}</h1>    
  </div>
</template>

<script>
export default {
  name: "MyComponent",
  props: {
    greeting: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color: red;
}
</style>
