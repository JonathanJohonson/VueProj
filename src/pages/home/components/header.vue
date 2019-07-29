<template>
  <div class="header">
    <div class="header-left">返回</div>
    <div class="header-input">input</div>
    <div class="header-right">城市</div>
  </div>
</template>

<script>
export default {
  name: 'homeheader'
}
</script>

<style lang='stylus' scoped>
  .header
    background-color #00bcd4
    color #fff
    display flex
    height 1.88rem
    padding-top 0.7rem
    .header-left
      width 3rem
      padding-left 1rem
      margin-top 0.2rem
      float left
    .header-input
      color black
      font-size 1.125rem
      margin-top 0
      marigin-right 3rem
      padding-left 0.3rem
      background-color #ffffff
      height 1.5rem
      border-radius 0.5rem
      flex 1
    .header-right
      margin-top 0.2rem
      width 3rem
      float right
      text-align center
</style>
