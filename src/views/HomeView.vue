<template>
  <div class="home">
    <HelloWorld msg="Food app" />
    <div class="phone">
      <phoneComp />
    </div>
  </div>
  <create />


</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'
import phoneComp from '@/components/phoneComp.vue'
import create from '@/components/Create.vue'
export default {
  name: 'HomeView',
  components: {
    HelloWorld, phoneComp,create
  }
}
</script>

<style lang="scss" scoped>
.home {
  background: url(../assets/background1.png) no-repeat center center fixed;
  background-size: cover;
  height: 1250px;
  left: 0;
  overflow: hidden;
}

.phone {
  position: relative;
}
</style>