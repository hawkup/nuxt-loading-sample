<template>
  <div>Loading 4s</div>
</template>

<script>
export default {
  mounted() {
    setTimeout(() => {
      this.$nuxt.$loading.finish()
    }, 4 * 1000)
  }
}
</script>
