# ops-manager
首次学习go相关知识，搭建一个自学的东风运维平台
电脑为macpro，所有数据都在Mac上操作的

#npm模块

##1、安装npm与vue
```
brew install node
npm install -g cpm --registry=https://registry.npm.taobao.org
npm install -g webpack  
npm i -g @vue/cli-init
npm install -g @vue/cli
```

##2、引入element-ui
```
cat element-ui-test/src/main.js

// The Vue build version to load with the `import` command
// (runtime-only or standalone) has been set in webpack.base.conf with an alias.
import Vue from 'vue'
import App from './App'
import router from './router'

<font color="red">
#新增
import ElementUI from 'element-ui'
import 'element-ui/lib/theme-chalk/index.css'
</font>
Vue.config.productionTip = false

/* eslint-disable no-new */
new Vue({
  el: '#app',
  router,
  components: { App },
  template: '<App/>'
})

```
