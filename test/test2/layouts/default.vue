<template lang="pug">
  .wrapper
    Header
    .content
      Nuxt
    Footer
</template>

<script>
import Header from '@/components/header/Header'
import Footer from '@/components/footer/Footer'

export default {
  name: "default",
  components: {
    Header,
    Footer
  }
}
</script>

<style scoped>

</style>
