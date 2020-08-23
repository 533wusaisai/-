# taro使用问题



## 安装

###  使用 npm 安装 CLI 

##### $ npm install -g @tarojs/cli # 

### OR 使用 yarn 安装 CLI 

##### $ yarn global add @tarojs/cli 

### OR 安装了 cnpm，使用 cnpm 安装 CLI 

##### $ cnpm install -g @tarojs/cli

### 项目初始化

##### $ taro init myApp

#### npm 5.2+ 也可不全局安装的情况下使用npx创建项目模版

$ npx @tarojs/cli init myApp

![taro init myApp command screenshot](http://ww1.sinaimg.cn/large/49320207gy1g0u2e0uf8gj20vg0uw10f.jpg)



## 微信小程序

### 项目启动/编译

##### yarn dev:weapp

##### yarn build:weapp

##### $ npm run dev:weapp 

##### $ npm run build:weapp

### 仅限全局安装 

##### $ taro build --type weapp --watch 

##### $ taro build --type weapp 

### npx 用户也可以使用 

##### $ npx taro build --type weapp --watch 

##### $ npx taro build --type weapp

## 其他可见官网https://taro-docs.jd.com/taro/docs/GETTING-STARTED.html

# taro-UI

### cd myApp 

### npm install taro-ui

