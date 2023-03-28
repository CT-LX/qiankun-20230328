
## 推荐文章
- [qiankun 微前端方案实践及总结](https://juejin.cn/post/6844904185910018062)
- 构建主应用 vue create main-app
  - 主应用安装 qiankun
    - npm i qiankun -S
    - npm install vue-router

- 构建vue子应用  vue create child-vue
  - npm install vue-router

- 构建react子应用 npx create-react-app child-react
  - npm i react-router-dom


- 子应用暴露生命周期 路由base

- 在主应用main.js 注册微应用

注意事项：
  1. 项目名称根节点名称不能一样
  2. 需要配置跨域
  3. activeRule 激活微应用的规则
  4. 子应用暴露生命周期且和独立运行
