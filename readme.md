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


## 3. 包使用
### 3.1 下载包
```
git clone https://github.com/qingbing/js-pack-demo.git
```

### 3.2 修改 package.json 里面的相应信息
如果不是制作 npm 包，这些信息也可不在意
- name
- description
- keywords
- author

### 3.3 安装依赖包
```
npm install
```

### 3.4 运行代码（代码编辑并调试）
```
npm run dev
```

### 3.5 发布包
每次发布包的时候，务必修改 package.json 中的 version ，否则不能上传
```
npm publish --access public
```

### 3.6 撤销发布包（必须在24小时内）
值的注意的是，即使发布包撤销，撤销的发布版本也不能再次发布（会报错），以免有人已经使用了这个版本
```
npm unpublish --force
```