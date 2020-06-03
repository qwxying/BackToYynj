<template>
  <view class="search-wrapper">
    <view class="search-code"><image class="img" src="../../../../static/tab/saoma.svg" mode="widthFix"></image></view>
    <view class="search">
      <image class="search-img" src="../../../../static/tab/sousuo.svg" mode="widthFix"></image>
      <input class="text" type="text" placeholder="请输入文字" disabled="" />
    </view>
    <view class="search-code"><image class="img" src="../../../../static/tab/xiaoxi.svg" mode="widthFix"></image></view>
  </view>
</template>

<script>
export default {
  // name: 'search'
};
</script>

<style scoped>
.search-wrapper {
  display: flex;
  justify-content: space-between;
  height: 70upx;
  align-items: center;
  padding: 30upx 0;
  background: linear-gradient(to top, #ffe566 10%, #ffd300 100%);
}
.search-code {
  width: 50upx;
  height: 50upx;
  padding: 0 15upx;
}
.search-code .img {
  width: 50upx;
  height: 50upx;
}
.search {
  height: 70upx;
  line-height: 70upx;
  width: 100%;
  display: flex;
  align-items: center;
  background-color: #fff7d4;
  border-radius: 50upx 0 50upx 50upx;
}
.search-img {
  width: 40upx;
  height: 40upx;
  margin: auto 20upx;
}
.search .text {
  text-align: center;
  line-height: 70upx;
  height: 70upx;
  font-size: 30upx;
  width: 100%;
}
</style>
