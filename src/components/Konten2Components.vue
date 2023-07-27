<script setup>
import { TheCard } from 'flowbite-vue'
</script>
<template>
<br>
<div class="grid grid-flow-col m-11  mr-1 grid-cols-1-max">
  <div> 
    <the-card variant="image" img-src="PICTURES/pexels-photo-3020919.webp" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Coffe Sweet</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
      $ 66.00
    </p>
  </the-card>
</div>
<br>
  <div>
     <the-card variant="image" img-src="PICTURES/pexels-photo-977846.jpeg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Coffe Expreso</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
      $ 48.10
    </p>
  </the-card>
  </div>
  <br>
  <div>
     <the-card variant="image" img-src="PICTURES/pexels-photo-3371220.webp" img-alt="Desk" >
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Coffe Mix </h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
      $ 43.00
    </p>
  </the-card>
  </div>
  <br>
</div>

</template>
