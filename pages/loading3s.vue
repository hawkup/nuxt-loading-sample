<template>
  <div>Loading 3s</div>
</template>

<script>
export default {
  mounted() {
    setTimeout(() => {
      this.$nuxt.$loading.finish()
    }, 3 * 1000)
  }
}
</script>
