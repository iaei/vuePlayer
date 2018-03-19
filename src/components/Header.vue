<template>
  <div class="m-header">
      <div class="icon"></div>
      <h1 class="text">Chicken Music</h1>
  </div>
</template>

<script>
export default {
  name: "mHeader"
};
</script>

<style lang="less" scoped>
  @import "../common/styles/variable";

  .m-header {
    height: 60px;
    background-color: @color-theme;
    color: @color-font;
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>
