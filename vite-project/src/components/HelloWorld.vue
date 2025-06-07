<script setup>
import { ref } from 'vue'


defineProps({
  msg: String,
})
</script>

<template>
<div class="container">
  <h1>Welcome</h1>
  <button>Click me!</button>
</div>

  
</template>

<style scoped>
h1{
  color: #42b883;
  font-size: 5em;
  text-align: center;
  margin-top: 20px;
  font-family: "Jersey 10", sans-serif;
  font-weight: 400;
  font-style: normal;
}
button{
  background-color: #42b883;
  color: white;
  border: none;
  padding: 10px 20px;
  font-size: 1em;
  cursor: pointer;
  font-family: "Jersey 10", sans-serif;
  font-weight: 400;
  font-style: normal;
}
.container {
  display: flex;
  flex-direction: column;
  align-content: center;
}
img {
  border-radius:12px
}
</style>
