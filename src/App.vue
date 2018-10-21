<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <list-viewer></list-viewer>>
    <button-counter customMessage="Hi!"></button-counter>
    <button-counter customMessage="Hello!"></button-counter>
    <my-component greeting="Hello"/>
    <text-reverser></text-reverser>
    <checkbox-example></checkbox-example>
    <fading-component></fading-component>
    
    <hello-world msg="Welcome to Your Vue.js App"/>
    
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import MyComponent from "./components/MyComponent.vue";
import ButtonCounter from "./components/ButtonCounter.vue";
import ListViewer from "./components/ListViewer.vue";
import TextReverser from "./components/TextReverser.vue";
import CheckboxExample from "./components/CheckboxExample.vue";
import FadingComponent from "./components/fading-component.vue";

export default {
  name: "app",
  components: {
    HelloWorld,
    MyComponent,
    ButtonCounter,
    ListViewer,
    TextReverser,
    CheckboxExample,
    FadingComponent
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
