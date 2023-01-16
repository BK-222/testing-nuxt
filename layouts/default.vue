<template>
  <div class=text-blue-300>
    <navbar></navbar>
    <nuxt></nuxt>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
export default {
  head: function() {
    return {
      titleTemplate: '%s - SEO optimised Vue-meta title.' 
    }
  }, 
  meta: [
    {
      hid: 'description', 
      name: 'description', 
      content: 'some content'
    }
  ], 
  components: {
    Navbar
  } 
}
</script>