<template>
  <div>
    <h1>{{ title }}</h1>
    <span @click="openOptions">...</span>
  </div>
</template>

<script>
  export default {
    name : "Card",
    data(){
      return {
          cardtitle : this.title
      }
    },
  props: ["title"],
  methods: {
    openOptions: function()
    {
      alert("options have been loaded");
    }
  }
};
</script>

<style scoped lang="scss"></style>
