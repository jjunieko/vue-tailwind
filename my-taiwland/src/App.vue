<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <HelloWorld msg="Teste em vue" />
</template>



<script>
import HelloWorld from './components/HelloWorld.vue'
import Addnew from'./components/Addnew.vue'


export default {
  name: 'App',
  components: {
    Addnew,
    HelloWorld
    
  }
}
</script>
