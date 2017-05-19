<template>
  <div>
    <a-head></a-head>
    <router-view></router-view>
    <!--<a-foot></a-foot>-->
  </div>
</template>

<script>
import aHead from '../components/ahead'
export default {
  name: 'hello',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components:{
    aHead
  }
}

</script>


<style scoped>

</style>
