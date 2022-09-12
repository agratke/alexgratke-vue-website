<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

</script>

<template>
  <img src='../assets/head.jpg' width="450" height="450"/>
  <h3>{{msg}}</h3>

  <p></p>
</template>

<style scoped>
img {
  border-radius: 50%;
}
</style>
