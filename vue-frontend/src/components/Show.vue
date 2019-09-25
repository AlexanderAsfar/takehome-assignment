<template>
  <!-- PART 4: Add your code here -->
  <div>
    {{name}} <counter v-bind:init_count="this.episodes_seen"/>
  </div>
</template>

<script>
// PART 4: Add your code here
import Counter from "./Counter.vue";
export default {
  components:{
    Counter
  },
  props:{
    id: Number,
    name: String,
    episodes_seen: Number
  }
};
</script>

<style>
</style>
