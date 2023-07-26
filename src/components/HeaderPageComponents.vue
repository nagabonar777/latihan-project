<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
  {
    'src': 'PICTURES/iklan1.jpg',
    'alt': 'Picture 1',
  },
  {
    'src': '/PICTURES/kopi2.jpg',
    'alt': 'Picture 2',
  },
  {
    'src': '',
    'alt': 'Picture 3',
  },
  {
    'src': '',
    'alt': 'Picture 4',
  },
  {
    'src': '',
    'alt': 'Picture 5',
  },
]
</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
</template>

<style>
.pictures{
  border-width: 12;
}
</style>
