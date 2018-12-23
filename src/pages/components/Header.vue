<template>
  <div class="header">
    <div class="header-left">返回</div>
    <div class="header-input">输入城市景点游玩主题</div>
    <div class="header-right">城市</div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
  // 1rem = 16px
  .header
    display: flex
    height: 3rem
    line-height: 3rem
    background: #00bcd4
    color: #fff
    .header-left
      width: 3.5rem
      float: left
    .header-input
      flex: 1
      height: 2rem
      line-height: 2rem
      margin-top: .5rem
      margin-bottom: .5rem
      background: #fff
      border-radius: .3rem
      color: #ccc
    .header-right
      width: 4rem
      float: right
      text-align: center
</style>
