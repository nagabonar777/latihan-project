<script setup>
import { TheCard } from 'flowbite-vue'
</script>
<template>
  <div class="grid grid-flow-col m-11 mr-1 grid-cols-1-max">
  <div><the-card variant="image" img-src="PICTURES/pexels-photo-2396220.jpeg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-700 dark:text-white">Moccachino Belgian</h5>
    <p class="font-normal text-gray-700 dark:text-gray-200">
      $ 45.00
    </p>
  </the-card>
</div>
  <div>
    <the-card variant="image" img-src="PICTURES/pexels-photo-3230010.jpeg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Coffe Pretty Look</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
      $ 37.00
    </p>
  </the-card>
  </div>
  <div>
    <the-card variant="image" img-src="PICTURES/pexels-photo-3491211.webp" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Coffe Starbucks</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
      $ 54.00
    </p>
  </the-card>
</div>

</div>
<br>


</template>
