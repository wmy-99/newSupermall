<template>
  <div class="main-tab-bar">
    <tab-bar>
      <tab-bar-item path="/home" activeColor="pink">
        <img slot="item-icon" src="../../assets/img/tabbar/home.svg" alt="">
        <img slot="item-icon-active" src="../../assets/img/tabbar/home_active.svg" alt="">
        <div slot="item-text" >首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category" activeColor="pink">
        <img slot="item-icon" src="../../assets/img/tabbar/category.svg" alt="">
        <img slot="item-icon-active" src="../../assets/img/tabbar/category_active.svg" alt="">
        <div slot="item-text" >分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart" activeColor="pink">
        <img slot="item-icon" src="../../assets/img/tabbar/shopcart.svg" alt="">
        <img slot="item-icon-active" src="../../assets/img/tabbar/shopcart_active.svg" alt="">
        <div slot="item-text" >购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile" activeColor="pink">
        <img slot="item-icon" src="../../assets/img/tabbar/profile.svg" alt="">
        <img slot="item-icon-active" src="../../assets/img/tabbar/profile_active.svg" alt="">
        <div slot="item-text" >我的</div>
      </tab-bar-item>
    </tab-bar>

  </div>
</template>

<script>
import TabBarItem from '../common/tabbar/TabBarItem'
import TabBar from "../common/tabbar/TabBar"

export default {
    name: "MainTabBar",
    components: {
      TabBarItem, TabBar
    }
}
</script>

<style>

</style>