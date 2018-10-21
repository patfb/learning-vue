<template>
    <div class="ListViewer">        
        <li v-for="item of items" :key="item.id">
            {{ item.title}}
        </li>
        
  </div>
</template>

<script>
export default {
  name: "list-viewer",
  data: () => {
    return {
      items: [
        { id: 1, title: "apples" },
        { id: 2, title: "bananas" },
        { id: 3, title: "mangoes" }
      ]
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
