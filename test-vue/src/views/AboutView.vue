<script setup lang="ts">
// import Counter from 'common/src/components/Counter'
import { filterNumber } from 'common/src/service/common'
import { h } from 'vue';
import TestCounter from '@/components/TestCounter.vue';

// const ReactCounter = h(Counter);
const str = 'sdb32312b23buuk24bk42bk4b44';
</script>

<template>
  <div class="about">
    <h1>This is an about page</h1>
    <h2>wow</h2>
    <div>
      <TestCounter />
      <!-- <ReactCounter /> -->
      {{ filterNumber(str) }}
    </div>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
