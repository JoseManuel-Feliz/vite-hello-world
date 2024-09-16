<script>
import HelloWorld from './components/AppTitle.vue'
import Jumbotron from './components/AppHero.vue'

export default{
  components:{
HelloWorld,
Jumbotron
  },
  data(){
    return{
      
    }
  }
}
</script>

<template>
  <div>
  <HelloWorld/>
<Jumbotron/>
  </div>
</template>

<style scoped>

</style>
