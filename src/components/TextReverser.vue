<template>
  <div class="textreverser">
    <input type="text" v-model="text">
    <button v-on:click="reverseText">Click to reverse</button>
    
  </div>
</template>

<script>
export default {
  name: "text-reverser",
  data: () => ({
    text: "Default text"
  }),
  methods: {
    reverseText() {
      this.text = this.text
        .split("")
        .reverse()
        .join("");
    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
