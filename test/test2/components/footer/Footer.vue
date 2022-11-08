<template lang="pug">
  div
    .footer
      .footer__container
        p {{ name }}
        p {{ github }}

</template>

<script>
export default {
  name: "Footer",
  data() {
    return {
      name: 'Хафизова Алина Руслановна',
      github: 'https://github.com/Alina99Stalk/Test-Etton'
    }
  }
}
</script>

<style scoped>

</style>
