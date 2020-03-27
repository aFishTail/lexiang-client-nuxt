<template>
  <div class="container">
    <div class="home">
      <!-- <nuxt-link to="/login">登录</nuxt-link> -->
    </div>
  </div>
</template>

<script>
export default {
  components: {
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
  background: no-repeat center url('~assets/imgs/home_bg.png');
  background-size: cover;
}
</style>
