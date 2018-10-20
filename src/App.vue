<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <ListViewer></ListViewer>
    <ButtonCounter customMessage="Hi!"></ButtonCounter>
    <ButtonCounter customMessage="Hello!"></ButtonCounter>
    <MyComponent greeting="Hello"/>
    <TextReverser></TextReverser>
    <checkbox-example></checkbox-example>
    
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import MyComponent from "./components/MyComponent.vue";
import ButtonCounter from "./components/ButtonCounter.vue";
import ListViewer from "./components/ListViewer.vue";
import TextReverser from "./components/TextReverser.vue";
import CheckboxExample from "./components/CheckboxExample.vue";

export default {
  name: "app",
  components: {
    HelloWorld,
    MyComponent,
    ButtonCounter,
    ListViewer,
    TextReverser,
    CheckboxExample
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
