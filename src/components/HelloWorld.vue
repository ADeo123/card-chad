<template>
<div class="mainWrapper">
  <h1 id="heading"> Penn State University </h1>
  <img src="https://www.psu.edu/psu-edu-assets/images/shared/psu-mark.svg" width="400" class="image">
  <h2>Description</h2>
  <p1>The Penn State University logo showing the Nittany Lion. </p1>
  <button> <a href="https://hax.psu.edu"> Details
  </a> </button> 
</div>
</template>

<script setup>
import { defineProps, reactive } from 'vue';


const state = reactive({ count: 0 });
</script>


<style scoped>
a {
  color: #42b983;
}
</style>
