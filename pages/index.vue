<template>
  <div class="page">
    <background>
      <template v-slot:header>
        <div class="bar">
          <ul>
            <li>首页</li>
            <li>关于</li>
            <li>
              <svg class="icon" aria-hidden="true">
                <use xlink:href="#iconlogo"></use>
              </svg>
            </li>
            <li @click="goLogin">登录</li>
            <li @click="goRegister">注册</li>
          </ul>
        </div>
      </template>
    </background>
  </div>
</template>

<script>
export default {
  name: 'home',
  components: {
    background: () => import('../components/background.vue')
  },
  methods: {
    goLogin () {
      this.$router.push({
        name: 'login'
      })
    },
    goRegister () {
      this.$router.push({
        name: 'login'
      })
    },
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
}
.bar {
  ul {
    display: flex;
    li {
      list-style: none;
      color: #fff;
      font-size: 26px;
      padding: 60px;
      cursor: pointer;
      // &:nth-of-type(3){
      //   padding: 0;
      // }
      svg{
        width: 120px;
        height: 40px;
      }
    }
  }
}
</style>
