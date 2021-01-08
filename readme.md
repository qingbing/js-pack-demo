# javascript 开发pack-demo包

## 1. 该包包含了常用的打包组件，执行命令可直接打包，含的打包组件
- npm install -D webpack webpack-cli : 打包主包
- npm install -D style-loader css-loader : css和style打包
- npm install -D html-webpack-plugin : html打包
- npm install -D file-loader : 静态资源打包
- npm install -D babel-loader @babel/core @babel/preset-env : 解决浏览器兼容
- npm install -D webpack-dev-server : 全自动打包和刷新页面 (开始命令 : webpack-dev-server --open)

## 2. 部署的基础命令
### 2.1 开发热加载
```
npm run dev
```

### 2.2 打包命令
```
npm run build
```

### 2.3 查看 webpack 版本
```
npm run pack-version
```

### 2.4 文件改动自助打包
```
npm run watch
```

### 2.5 运行主文件
```
npm run start
```
