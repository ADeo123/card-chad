<template>
  <h1>{{ msg }}</h1>


<button class="deleteBtn">Delete Card</button>
<button class="duplicateBtn"> Duplicate Card</button>
<button class="changeColorBtn"> Background Color</button>
<button class="ChangeHeadingBtn">Change Heading</button>

<div>
  <h1 id="heading"> Penn State University </h1>
  <img src="https://www.psu.edu/psu-edu-assets/images/shared/psu-mark.svg" width="400" class="image">
  <h2>Description</h2>
  <p1>The Penn State University logo showing the Nittany Lion. </p1>
  <button> <a href="https://hax.psu.edu"> Details
  </a> </button> 
</div>

  <p>
    <a href="https://vitejs.dev/guide/features.html" target="_blank">
      Vite Documentation
    </a>
    
    <a href="https://v3.vuejs.org/" target="_blank">Vue 3 Documentation</a>
  </p>

  <button type="button" @click="state.count++">count is: {{ state.count }}</button>
  <p>
    Edit
    <code>components/HelloWorld.vue</code> to test hot module replacement.
  </p>
</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String
})

const state = reactive({ count: 0 })
</script>

<script>


</script>

<style scoped>
a {
  color: #42b983;
}
</style>
