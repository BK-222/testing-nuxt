<template>
  <div>
    Event #{{ this.$route.params.id }}
  </div>
</template>
<script>
export default {
  head: function() {
    return {
      title: `Event #{this.id}`, 
      meta: [
        {
          hid: 'description', 
          name: 'description', 
          content: `Content of #{this.id}`
        }
      ], 
    }
  }, 
  computed: {
    id: function() {
      return {
        id: this.$route.params.id
      }
    }
  } 
}
</script>