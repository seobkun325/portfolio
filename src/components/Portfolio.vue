<template>
  <button @click="count">{{ num }}</button>
</template>

<script setup>
import {ref} from 'vue'

const num = ref(0)
  const count = () => {
  num.value++
}
</script>

<style>
button {
  width: 30px;
  height: 30px;
}
</style>

