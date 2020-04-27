<template>
  <div class="home">
    <div class="demo">我是什么</div>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
<style lang='less'>

.home{
  .demo{
    font-size: @h-font-size-lg;
  }
}
</style>
