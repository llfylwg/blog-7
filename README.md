# 【大前端】分享记录，先列个大纲之后慢慢补坑

## 01. JS 基础

- [JS面向对象](https://github.com/Godiswill/blog/issues/8)（封装、继承、多态）
- [实现继承的几种方式](https://github.com/Godiswill/blog/issues/9)（原型、构造函数、组合、寄生组合、类式、拷贝继承）
- [一图理解原型链](https://github.com/Godiswill/blog/issues/10)（实例对象是如何与自己的构造函数、`Function`、`Object` 串联起来的）
- 常用设计模式
- 常考查算法
- [《ECMAScript 6 入门教程》](https://es6.ruanyifeng.com/)
- [你真的懂事件循环吗](https://github.com/Godiswill/blog/issues/17)

## 02. CSS 基础

- [BFC块级格式化上下文](https://github.com/Godiswill/blog/issues/11)
- 动画`Animation`，过渡`transition`
- 常用布局
- 移动适配 [amfe-flexible 分析](https://github.com/Godiswill/blog/issues/13)

## 03. 前端框架原理

- [源码分析：react hook 最佳实践](https://github.com/Godiswill/blog/issues/18)
- redux、react-redux、redux-soga 源码分析
- Vue 双向绑定原理
- React diff算法思路
- mobx、redux 状态管理实现思路
- React fiber 原理

## 04. 前端性能优化

- [前端极致性能优化手册大全](https://github.com/Godiswill/blog/issues/15)
- [防抖debounce与节流throttle](https://github.com/Godiswill/blog/issues/12)
- [性能优化——关键路径渲染优化](https://github.com/Godiswill/blog/issues/1)
- [HTTP 缓存](https://github.com/Godiswill/blog/issues/2)
- [什么导致强制布局/重排](https://github.com/Godiswill/blog/issues/3)
- [布局边界 Layout Boundaries](https://github.com/Godiswill/blog/issues/4)（微优化）
- [如何构建 60FPS 应用](https://github.com/Godiswill/blog/issues/5)
- [一帧剖析](https://github.com/Godiswill/blog/issues/14)

## 05. JS服务端

- 跨域jsonp、cors
- koa 源码分析
- egg 实战

## 06. web 安全问题

- XSS
1. 存储型
1. 反射型
1. DOM型
- CSRF
- SSRF

## 07. 开发工具

- chrome devtool
- charles

## 08. 前端工程化

### 公共模板及文档建设

- vue-cli、create-react-app的原理和实现
- node 命令行 commander、inquirer、chalk
- doc 生成工具
- 区块概念

### 仓库

- github/gitlab
- 私有npm
- docker hub

### 打包工具 webpack、rollup

- [rollup 打包实践](https://github.com/Godiswill/blog/issues/6)
- webpack loader/plugin 等实现细节

### 持续集成 -- 测试、构建、发布部署系统

1. 用户触发构建 -> Jenkins 执行任务 test/build/合master 打tag
1. 用户触发部署 -> Jenkins 执行任务 -> 推送 oss
1. 用户触发回滚 -> Jenkins 根据 tag 拉代码覆盖 oss

html 不缓存 其他静态资源 hash 文件名长缓存。

- Jenkins
- git webhook
- CDN

### 错误监控系统

- [错误监控原理分析](https://github.com/Godiswill/blog/issues/7)

### 性能监控系统

- 性能监控指标

### 前端工程部署

- pm2
- docker + ftp
- docker hub
- docker compose + git
- k8s

### 前端微服务

- iframe
- nginx 代理路由
- npm 包
