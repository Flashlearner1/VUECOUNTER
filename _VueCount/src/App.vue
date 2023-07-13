<script setup>
import { ref } from 'vue'
const count = ref(0)
</script>

<template>
  <h4>Current count is : </h4>
  <h1>{{ count }}</h1>
  <button @click="count++">+</button>
  <button @click="count--">-</button>
</template>

//"count" is a javascript//

<style scoped>
button {
  font-weight: bold;
}
</style>