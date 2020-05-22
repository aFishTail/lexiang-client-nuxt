<template>
  <div class="backgroud">
    <span class="title">{{message}}</span>
  </div>
</template>

<script>
export default {
  name: 'backgroud',
  data() {
    return {
      message: '乐享，乐于分享'
    }
  }
}
</script>

<style>
</style>

<style lang="less" scoped>
.backgroud {
  width: 100%;
  height: 100%;
  background: url('~assets/imgs/home_bg.png');
  display: flex;
  align-items: center;
  justify-content: center;
  .title {
    font-size: 3.5em;
    color: #fff;
    font-weight: 600;
    letter-spacing: 0.12em;
    /* margin: auto; */
  }
}
</style>
