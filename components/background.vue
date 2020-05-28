<template>
  <div class="comp-backgroud">
    <slot name="header"></slot>
    <slot name="main">
      <span class="title">{{ message }}</span>
    </slot>
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
.comp-backgroud {
  width: 100%;
  height: 100%;
  background: url('~assets/imgs/home_bg.png');
  display: flex;
  flex-direction: column;
  align-items: center;
  // justify-content: center;
  .title {
    margin: 240px 0;
    font-size: 3.5em;
    color: #fff;
    font-weight: 600;
    letter-spacing: 0.12em;
    /* margin: auto; */
  }
}
</style>
