<template>
  <div class="container">
    <div class="left">欢迎进入登录页面</div>
    <div class="right">
      <backgroud/>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
export default {
  components: {
    backgroud: () => import('../components/backgroud')
  }
}
</script>

<style lang="less">
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: space-between;
  align-items: center;
  text-align: center;
  .left{
  width: 30vw;
}
  .right{
    width: 70vw;
    height: 100vh;
  }
}
</style>
