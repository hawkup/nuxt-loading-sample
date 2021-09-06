<template>
  <div>Loading 5s</div>
</template>

<script>
export default {
  mounted() {
    setTimeout(() => {
      this.$nuxt.$loading.finish()
    }, 5 * 1000)
  }
}
</script>
