<template>
  <div class="page">
    <div class="login-wrapper">
      ddd
      <loginComp/>
    </div>
    <background>
    </background>
  </div>
</template>

<script>
export default {
  name: 'login',
  components: {
    background: () => import('../components/background.vue'),
    loginComp: () => import('../components/login-comp.vue')
  }
}
</script>

<style lang="less" scoped>
.icon {
  width: 1em;
  height: 1em;
  vertical-align: -0.15em;
  fill: currentColor;
  overflow: hidden;
}
.page {
  margin: 0 auto;
  height: 100vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  .login-wrapper{
    width: 38vw;
  }
}
</style>
