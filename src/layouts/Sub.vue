<template>
  <div class="container">
    
    <v-menu></v-menu>
    <sub-top></sub-top>
    <slot></slot>
    <p>이 페이지는 서브레이아웃 입니다.</p>
  </div>
</template>

<script>
  import VLink from '../components/VLink.vue'
  import VMenu from '../components/VMenu.vue'  
  import SubTop from '../components/SubTop.vue'

  export default {
    components: {
      VLink,
      VMenu,
      SubTop
    }
  }
</script>

<style scoped>
  .container {
    max-width: 600px;
    margin: 0 auto;
    padding: 15px 30px;
    background: #f9f7f5;
    border:1px solid #aaa;
  }
</style>
