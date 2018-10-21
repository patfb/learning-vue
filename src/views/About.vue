<template>
  <div class="about">
    <h1>This is an about page</h1>
    <button-counter></button-counter>
    
  </div>
</template>

<script>
import ButtonCounter from "@/components/ButtonCounter.vue";

export default {
  name: "about",
  components: {
    ButtonCounter
  }
};
</script>