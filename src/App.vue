<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  
  <HelloWorld msg="Vite + Vue"/>
  <div class="container mx-auto max-w-7xl">
 <div v-for="x in 20">
<div class="bg-gray-500 text-sm text-white rounded-md p-4" role="alert">
  <span class="font-bold">Secondary</span> alert! You should check in on some of those fields below.
</div>
<div class="bg-blue-500 text-sm text-white rounded-md p-4" role="alert">
  <span class="font-bold">Info</span> alert! You should check in on some of those fields below.
</div>
<div class="bg-green-500 text-sm text-white rounded-md p-4" role="alert">
  <span class="font-bold">Success</span> alert! You should check in on some of those fields below.
</div>
<div class="bg-red-500 text-sm text-white rounded-md p-4" role="alert">
  <span class="font-bold">Danger</span> alert! You should check in on some of those fields below.
</div>
<div class="bg-orange-500 text-sm text-white rounded-md p-4" role="alert">
  <span class="font-bold">Warning</span> alert! You should check in on some of those fields below.
</div>
<div class="bg-white text-sm text-gray-600 rounded-md p-4" role="alert">
  <span class="font-bold">Light</span> alert! You should check in on some of those fields below.
</div>
</div>
  </div>
</template>


