# Vue 3 + Vite

## 文件目录解析

1. index.html：项目入口文件
2. package.json：管理项目依赖和配置的文件
3. public 目录：放置静态资源，比如 logo 等图片
4. vite.config.js：和 Vite 相关的所有工程化配置
5. src：项目源码目录

## 项目架构

1. 基于 Node.js 生态
2. 开发工具：使用 VSCode （编辑器） + Volar （语法提示工具）
3. 调试工具：Chrome + Dev Tools
4. 工程化工具：使用 Vite
   1. 代码规范
      1. ESLint
      2. Prettier
   2. 研发规范
      1. Git
5. 应用开发语言及其生态：
   1. Vue 3
   2. 数据管理：Vuex ： `npm install vue-router@next`
   3. 路由管理：Vue-router ： `npm install vuex@next`
   4. CSS 预处理
   5. 网络请求
   6. 组件库
6. 单元测试
7. 部署

![img](https://static001.geekbang.org/resource/image/3c/2c/3c9c01bf8917b85c469d086d4d0eb52c.jpg?wh=1385x968)

## 源码管理规范

```
├── src
│   ├── api            数据请求
│   ├── assets         静态资源
│   ├── components     组件
│   ├── pages          页面
│   ├── router         路由配置
│   ├── store          vuex数据
│   └── utils          工具函数
```
