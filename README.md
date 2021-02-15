# 华科猫可梦(HUSTCATS)
基于Taro3开发的微信小程序, 是一个聚焦华科校园里的喵星人，编写猫咪图鉴，建立猫咪科普、救助的平台。
## 安装
### 安装 Taro 开发工具 @tarojs/cli
```javascript
# 使用 npm 安装 CLI
$ npm install -g @tarojs/cli
# OR 使用 yarn 安装 CLI
$ yarn global add @tarojs/cli
# OR 安装了 cnpm，使用 cnpm 安装 CLI
$ cnpm install -g @tarojs/cli
```
### 安装依赖
```
npm install
```
### 构建并监听微信小程序
```
taro build --type weapp --watch
```
然后打开微信小程序开发者工具, 选择项目根目录编译即可 
## 目录结构
```
├── dist                   编译结果目录
├── config                 配置目录
|   ├── dev.js             开发时配置
|   ├── index.js           默认配置
|   └── prod.js            打包时配置
├── src                    源码目录
|   ├── pages              页面文件目录
|   |   ├── index          index 页面目录
|   |   |   ├── index.vue  index 页面逻辑
|   |   |   └── index.css  index 页面样式
|   ├── app.css            项目总通用样式
|   ├── app.js             项目入口文件
|   ├── assets             静态资源目录
|   |   ├── images         图片目录
|   |   └── styles         公共scss目录
|   ├── components         组件目录
|   ├── utils              工具函数目录
|   |   └── axios.ts       使用类axios语法封装网络请求
|   └── server             网络请求目录
└── package.json
```
## 在线预览
这里是二维码
## 使用微信开发者工具注意事项
- 需要设置关闭 ES6 转 ES5 功能，开启可能报错
- 需要设置关闭上传代码时样式自动补全，开启可能报错
- 需要设置关闭代码压缩上传，开启可能报错