<script setup lang="ts">
import TestCounter from 'test-vue/src/components/TestCounter.vue'
import { filterNumber } from 'common/src/service/common'
</script>

<template>
  <div class="about">
    <h1>This is an about page {{ filterNumber('h349hf74gf43gfg9hf9h49') }}</h1>
    <TestCounter />
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
