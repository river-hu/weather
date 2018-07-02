<template>
  <div class="home">
    <img src="../assets/logo.png">
    <HelloWorld :msg="msg"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  },
  data(){
    return{
      msg:"Welcome to Your Vue.js App 0"
    }
  }
}
</script>
