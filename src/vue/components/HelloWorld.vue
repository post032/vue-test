<template>
  <h1>{{ msg }}</h1>
  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
  </div>
  <Todos/>
</template>

<script setup>
import Todos from './Todos.vue'
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>


