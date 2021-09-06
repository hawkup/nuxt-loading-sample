<template>
  <div>Loading 2s</div>
</template>

<script>
export default {
  mounted() {
    setTimeout(() => {
      this.$nuxt.$loading.finish()
    }, 2 * 1000)
  }
}
</script>
