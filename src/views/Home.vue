<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome" dumbBoi="James" @ChrisIsPrettyGoodJustNotAsGoodAsTheOtherDevelopers="number = $event"/>
    {{number}}
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  },
  data(){
    return{
      number: 69
    }
  }
}
</script>
