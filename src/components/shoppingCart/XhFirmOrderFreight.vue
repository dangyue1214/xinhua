<template>
  <div class="XhFirmOrderFreight">
      <div class="XhFirmOrderFreight-left">
        <p class="XhFirmOrderFreight-left-text">运费</p>
        <p class="XhFirmOrderFreight-left-desc">已选0张</p>
      </div>
      <div class="XhFirmOrderFreight-right">
        <div class="XhFirmOrderFreight-right-price-wrapper">
          <p class="XhFirmOrderFreight-right-price">快递 ￥6.00</p>
        </div>
        <div class="XhFirmOrderFreight-right-icon-wrapper">
          <i class="iconfont">&#xe62d;</i>
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name : 'XhFirmOrderFreight'
}
</script>

<style scoped>
  .XhFirmOrderFreight {
    margin-top: .2rem;
    display: flex;
    justify-content:space-between;
    background: #fff;
    line-height: .98rem;
    font-size: .3rem;
  }
  .XhFirmOrderFreight-left {
    margin-left: .3rem;
    display: flex;
  }
  .XhFirmOrderFreight-right {
    display: flex;
    color: #999;
  }
  .XhFirmOrderFreight-left-desc {
    color: #999;
    margin-left: .2rem;

  }
  .XhFirmOrderFreight-right-icon-wrapper {
    margin-right: .3rem;
    margin-left: .2rem;
  }
</style>



