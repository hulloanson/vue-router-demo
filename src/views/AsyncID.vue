<template>
  <div class="asyncid">
  </div>
</template>

<script>

export default {
  name: 'Home',
  mounted() {
      // do your async stuff here
      (async () => {
        console.log(`Making request to /api/v1/statuses/${this.$route.params.id}`)
      })()
  },
}
</script>
