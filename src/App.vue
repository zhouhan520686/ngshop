<template>
  <div id="app">
    <ul class="footer-bar">
      <li class="foot-bar-item">
        <router-link to="/">首页</router-link>
        </li>
      <li class="foot-bar-item"><router-link to="/category">分类</router-link></li>
      <li class="foot-bar-item"><router-link to="/cart">购物车</router-link></li>
      <li class="foot-bar-item"><router-link to="/profile">我的</router-link></li>
    </ul>
    <router-view/>
  </div>
</template>

<script>
export default {
  
}
</script>
<style lang="scss" scoped>
.footer-bar {
  display: flex;
  background: #eeeeee;
  position: fixed;
  bottom: 0;
  width: 100%;
  height: 1.333333rem;
  line-height: 1.333333rem;
  .foot-bar-item {
    flex-grow: 1;
    text-align: center;
  }
}
</style>
