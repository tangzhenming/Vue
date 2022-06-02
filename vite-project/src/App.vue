<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from "./components/HelloWorld.vue";
</script>

<!-- 
  router-link 和 router-view 是由 vue-router 注册的全局组件
  router-link 负责跳转不同的页面，相当于 Vue 世界中的超链接 a 标签
  router-view 负责渲染路由匹配的组件
  我们可以通过把 router-view 放在不同的地方，实现复杂项目的页面布局
 -->

<template>
  <div>
    <router-link to="/">首页</router-link> |
    <router-link to="/about">关于</router-link>
  </div>
  <router-view></router-view>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
