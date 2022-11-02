<template>
  <div class="home">
    <HelloWorld msg="Food app" />
    <div class="phone">
      <phoneComp />
    </div>
  </div>
  <create />
  <explore />
  <Checkout />

  <div class="Footer">
    <Footer /> 
  </div>
  <EndPage/>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'
import phoneComp from '@/components/phoneComp.vue'
import create from '@/components/Create.vue'
import explore from '@/components/explore.vue'
import Checkout from '@/components/Checkout.vue'
import Footer from '@/components/Footer.vue'
import EndPage from '@/components/EndPage.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld, phoneComp, create, explore, Checkout, Footer,
    EndPage
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

.Footer {
  background: url(../assets/download.png) no-repeat center center fixed;
  background-size: cover;
  height: 500px;
  left: 0;
  overflow: hidden;
}
</style>