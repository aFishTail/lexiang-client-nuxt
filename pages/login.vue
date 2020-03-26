<template>
  <div class="container">
    <p>欢迎进入登录页面</p>
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
