底层架构

使用 vue-element-admin 模板作为开发的基础底座，其本身就具备了一些开发能力，比如 vue.js、element、vuerouter、vuex、（组件的封装）、axios（接口的封装）、sass（样式的处理）、vue-cli（脚手架的配置）、js-cookie

然后在此基础上实现 UI 层以及业务模块

UI 层的实现，使用的技术是：vue.js & element

业务模块包括：

登录、登出
主页模块
组织架构（弹层编辑）
角色管理（行内编辑）
员工管理（跳转编辑）
权限管理（权限应用）
首页图表（打包上线）

然后关于这些业务模块，使用的解决方案包括：
vue 持久化
axios 封装
方向代理
环境变量
异常处理
组件封装
nextTick 应用
set 应用
防抖应用
联合查询
excel 导入导出
云存储业务
路由权限
自定义指令
echarts 图表

开发所涉及的开发工具有：
vscode
vetur
eslint
git
sass
nginx