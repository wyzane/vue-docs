## vue环境搭建

### 1. 使用淘宝npm镜像(npm.taobao.org)
安装cnpm(由于npm在下载软件包时很慢):
npm install -g cnpm --registry=https://registry.npm.taobao.org

### 2. 安装命令行工具vue-cli
cnpm install -g vue-cli          # -g表示全局安装，同-global

### 3. 初始化项目, 创建一个基于webpack模板的新项目
vue init webpack(项目类型) my-project(项目名称)

### 4. 进入项目并安装依赖
cd my-project
cnpm install

### 5. 启动项目
npm run dev

### 6. 目录介绍
src: 源码文件
  App.vue: 第一个vue组件
  main.js: 入口文件
  componemts: 子组件所在目录
config: 环境配置文件
static: 静态文件

