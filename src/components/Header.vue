<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
  {
    'src': 'https://seuladogeek.com.br/wp-content/uploads/2022/02/Just-do-It-Nike-Logo.png',
    'alt': 'Picture 1',
  },
]
</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
</template>

<style>

</style>