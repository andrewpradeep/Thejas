<template>
    <div class="item" @click="this.click(id)">
        {{title}}
    </div>
</template>

<script>
export default {
  name : "Item",
  props: {
    id            : Number,
    title         : String,
    description   : String
  }
};
</script>

<style  scoped lang="scss">
  .item {
    color         : #444;
    background    : #ededed;
    border-radius : 5px;
    font-size     : 14px;
    padding       : 5px;
    margin        : 4px;
    text-align    : left;
  }
</style>