<template>
  <div>Loading 10s</div>
</template>

<script>
export default {
  mounted() {
    setTimeout(() => {
      this.$nuxt.$loading.finish()
    }, 10 * 1000)
  }
}
</script>
