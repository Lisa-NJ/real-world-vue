// Template Refs

<template>
  <div class="about">
    <h1>This is a play ground page</h1>
    <p ref="p">This is to show how to use ref</p>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
export default Vue.extend({
  mounted() {
    this.$refs.p.innerHTML = "Has been mounted successfully";
  },
});
</script>
