<template>
  <div>Loading 1s</div>
</template>

<script>
export default {
  mounted() {
    setTimeout(() => {
      this.$nuxt.$loading.finish()
    }, 1 * 1000)
  }
}
</script>
