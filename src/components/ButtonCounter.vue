<template>
  <div class="ButtonCounter">
    <button v-on:click="count++">{{ customMessage}} You clicked me {{ count }} times.</button>
  </div>
</template>

<script>
export default {
  name: "ButtonCounter",
  props: {
    customMessage: String
  },
  data: () => {
    return {
      count: 0
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h2 {
  color: blue;
}
</style>
