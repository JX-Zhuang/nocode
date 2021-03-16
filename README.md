### nocode
#### 背景
* 后台系统许多功能是类似的，比如：表单、列表等
* 布局基本类似，组件可以复用
* 新开发的页面，可以直接复制原有页面文件，稍加修改就能生成新的页面
#### 目标
* 提升开发效率
* 通过拖拽的方式生成新的页面
* 通过拖拽的方式修改原有页面
#### 使用场景
* 后台系统的顶部和侧边导航是固定的，暂时不需要修改
* 可以修改拖拽的组件的某些属性
* 支持撤销、反撤销、保存
#### 规划
##### Milestone 1
* 支持撤销、反撤销
* 支持`Table`、`Button`组件
* 支持下载或查看生成的页面代码
##### Milestone 2
* 生成的页面文件，保存到后台的`src/pages`目录下
* 支持生成对应的路由
* 支持`Input`、`Radio`、`Switch`、`Select`等组件
##### Milestone 3
* 加入更多的基础组件
* 自动保存到本地
##### Milestone 4
* 调用后端接口
#### 资料
##### GrapesJS
* https://github.com/artf/grapesjs
##### react-visual-editor
* https://github.com/brick-design/react-visual-editor