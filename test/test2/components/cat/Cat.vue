<template lang="pug">
  .card
    .card__text
      p.card__name {{ name }}
      p.card__price {{ price }}

</template>

<script>
export default {
  name: "Cat.vue",
  data() {
    return {
      name: 'Название',
      price: '14 900 р.'
    }
  }
}
</script>

<style scoped>

</style>
