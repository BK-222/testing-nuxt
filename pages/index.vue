<template>
	<div class="flex flex-col items-center justify-center">
    <p class="text-4xl text-zinc-500">Hello World!</p>
    <p class="text-2xl">Testing something else</p>
    <comp-one></comp-one>
  </div>
</template>

<script>
import CompOne from '@/components/NuxtLogo.vue'
export default {
  components: {
    CompOne
  } 
}
</script>
