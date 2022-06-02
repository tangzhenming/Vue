<template>
  <div>
    <h1 @click="add">{{ count }}</h1>
  </div>
</template>

<script setup>
// 使用 ref 返回响应式数据
// ref 返回的响应式数据需要修改 .value 才能生效
// script setup 标签中定义的变量和函数都可以直接在模板中直接使用
import { ref } from "vue";
let count = ref(1);
function add() {
  count.value++;
}
</script>

<style>
h1 {
  color: red;
}
</style>
