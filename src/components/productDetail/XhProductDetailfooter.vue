<template>
<!--  尾部-->
    <div>
      <div class="footerProductDetail">
        <div class="shoppProductDetail">
          <router-link to="/">
            <van-icon name="service-o" class="footerDetailfooterProductDetail" />
            <span>联系客服</span>
          </router-link>
        </div>
        <div>
          <router-link to="/XhShoppingCart">
            <van-icon name="shopping-cart-o" class="footerDetailfooterProductDetail" />
            <span>购物车</span>
          </router-link>
        </div>
        <p class="owProductsList"  >加入购物车</p>
        <p class="shProductsList"  >立即购买</p>
      </div>
    </div>
</template>

<script>
    export default {
        name: "XhProductDetailfooter"
    }
</script>

<style scoped>
  @import "../../assets/css/XhProductDetail.css";

</style>
