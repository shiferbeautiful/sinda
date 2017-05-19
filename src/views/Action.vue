<template>
  <div>
    <a-head></a-head>
    <router-view></router-view>
    <a-heads></a-heads>
    <afoot></afoot>
  </div>
</template>

<script>
import afoot from '../components/afoot'
import aHead from '../components/ahead'
import aHeads from '../components/headers'

export default {
  name: 'hello',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components:{
    aHead,

    aHeads,

    afoot

  }
}

</script>


<style scoped>

</style>
