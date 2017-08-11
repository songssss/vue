<template>
  <main-layout>
    <p>About page</p>
    <p>{{msg}}</p>
    <input v-model="sameText" placeholder="입력해보세요">
    <p>{{sameText}}</p>
  </main-layout>
</template>


<script>
  import MainLayout from '../layouts/Main.vue'

  export default {
    components: {
      MainLayout
    },
    data (){
      return {
        msg: 'hello!!!!',
        sameText:''
      }
    },
    created (){
      this.sameText = 'bye!'
    }
  }


</script>
