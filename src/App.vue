<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <Card v-bind:title="title"></Card>
  </div>
</template>

<script>
import Card from "./components/Card.vue";
export default {
  name: "app",
  components: {
    Card
  },
  data(){
    return {
      title: "Pradeep"
    };
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
