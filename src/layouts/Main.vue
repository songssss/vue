<template>
  <div class="container">
    <v-menu></v-menu>

    <slot></slot>
  </div>
</template>

<script>
  import VLink from '../components/VLink.vue'
  import VMenu from '../components/VMenu.vue'

  export default {
    components: {
      VLink,
      VMenu
    }
  }
</script>

<style scoped>
  .container {
    max-width: 600px;
    margin: 0 auto;
    padding: 15px 30px;
    background: #f9f7f5;
  }
</style>
