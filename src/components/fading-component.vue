<template>
    <div class="fading-component">
        <button v-on:click="show = !show">Fade text</button>
        <transition name="fade">
            <p v-if="show">This text fades</p>
        </transition>
    </div>
</template>

<script>
export default {
  name: "fading-component",
  data: () => ({
    show: true
  })
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.5s;
}
.fade-enter, .fade-leave-to /* .fade-leave-active below version 2.1.8 */ {
  opacity: 0;
}
</style>
