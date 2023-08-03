<template>
  <div>
    <!-- 二级路由出口：二级组件展示的位置 -->
    <router-view></router-view>

    <van-tabbar route active-color="#ee0a24" inactive-color="#000">
      <van-tabbar-item  icon="wap-home-o"><router-link to="/home">首页</router-link></van-tabbar-item>
      <van-tabbar-item  icon="apps-o"><router-link to="/category">分类页</router-link></van-tabbar-item>
      <van-tabbar-item  icon="shopping-cart-o"><router-link to="/cart">购物车</router-link></van-tabbar-item>
      <van-tabbar-item  icon="user-o"><router-link to="/user">我的</router-link></van-tabbar-item>
    </van-tabbar>
  </div>
</template>

<script>
export default {
  name: 'LayoutIndex'
}
</script>

<style>

</style>
