<script setup lang="ts">
import { ref } from 'vue';

const count = ref(0);
const handleClick = () => count.value++;
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ count }}</h1>
    <button @click="handleClick">Click me!!</button>
  </div>
</template>
