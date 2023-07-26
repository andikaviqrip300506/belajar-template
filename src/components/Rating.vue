<script setup>
import { Rating } from 'flowbite-vue'
</script>
<template>
    <div class="container">
    <Rating :rating="4">
      <template #besideText>
          <p class="ml-2 text-sm font-medium text-gray-500 dark:text-gray-400">4.95 out of 5</p>
        </template>
    </Rating>
    </div>
</template>

<style>
.container {
    text-align: center;
    align-content: center;
}
</style>

