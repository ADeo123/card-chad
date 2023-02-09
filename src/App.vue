<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3 + Vite" />
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>

div {
  text-align: center;
  border: 2px solid Black;
  padding: 8px 8px 32px 32px;
  width: 500px;
  height: 500px;
}
button {
  color: blue;
  padding: px 8px 8px 8px 8px;
  display: block;
  margin: auto
}
.btn:hover {
  background-color: blue; 
  color: white;
}
.btn:focus {
  background-color: blue; 
  color: white;
}
.image {
  padding: 8px 8px 32px 190px;
}
.heading{
  margin: 50px;
}
@media (min-width: 500px) and (max-width: 800px) {
  button {
    opacity: 0;
    display: none;
  }
}
@media (max-width: 500px) {
  div {
    font-size: 10px;
    image-size: auto;
  }
}

</style>
