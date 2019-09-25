<template>
  <p> 
    {{count}} <button v-on:click="count+=1"> Increment </button> <button v-on:click="count-=1"> Decrement </button>
  </p>
</template>

<script>
export default {
  props:{
    init_count: {
      type: Number,
      default:0
      }
  },
  data() {
    return {
      count: this.init_count
    };
  }
};
</script>

<style>
</style>

