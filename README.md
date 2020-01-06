# Quick Website with Antd and Umi  :rocket::rocket::rocket:  :man_pilot: :100: :+1:

当前分支： master

> 参考 [Ant Design Landing Website](https://landing.ant.design/index-cn)

# 开发构建

## 项目目录结构

```
├── /dist/                  # 项目输出目录
├── /src/                   # 项目源码目录
│ ├── /Home/                # 从ant design landing 上下载下来的代码
│ ├── /pages/               # 页面文件
│ │ ├── index.js            # 入口文件
│ │ └── index.css           # css
├── package.json            # 项目信息
├── README.md               # Readme
```

## 特性

- 基于react, ant-design, dva, umi, Mock 企业级管理门户最佳实践
- 基于 Antd UI 设计语言，提供后台管理系统常见使用场景
- 可以直接在ant design landing 编辑器上设计完毕只有，下载代码添加到该项目中运行
- 浅度响应式设计

## 主要技术

- Ant Design （UI框架）
- React（主要开发语言）
- Dva（动态加载Modal和路由，按需加载）
- ESLint（强制规范）
- UmiJS（前端开发框架）

## 快速开始

### 环境搭建

```
Step1: 安装Node.js
    #node.js 官网
    http://nodejs.cn/download/

    #Node.js 安装参看安装文档
    http://www.runoob.com/nodejs/nodejs-install-setup.html

Step2: 安装Yarn
    Tips: 这个主要是因为国内npm下载速度感人，所以使用yarn进行下载

    # 使用npm全局安装
    npm install yarn -g
```

### 克隆项目文件

```shell
  git clone https://github.com/SongFuZhen/quick_website_with_antd_landing.git
```

### 进入项目目录安装依赖

```shell
  cd code && yarn install 
```

该过程耗时比较长，耐心等待即可

---

### 项目运行

```shell
 # 使用 yarn 启动
 yarn dev 

 # 使用 npm 启动
 npm run dev
```

### 项目打包部署

```shell
# 使用 yarn 构建
yarn build

#使用 npm 构建
npm run build
```
