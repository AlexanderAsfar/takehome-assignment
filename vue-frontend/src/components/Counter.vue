<template>
  <p>I'm a Counter! <br/>
    {{count}}<br/>
    <button v-on:click="count+=1"> Increment </button> <button v-on:click="count-=1"> Decrement </button>
  </p>
</template>

<script>
export default {
  data() {
    return {
      count: 0
    };
  }
};
</script>

<style>
</style>

