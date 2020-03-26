<template>
  <div class="container">
    <div class="home">
      
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.home{
  width: 100vw;
  height: 100vh;
  background: url('~assets/imgs/home_bg.png');
}
</style>
