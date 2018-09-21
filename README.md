# gulp-rollup

gulp&amp;rollup 构建打包JS

## 快速开始

### 全局安装rollup和gulp

```sh
npm install --global rollup gulp-cli
```

### 打包app.js

```sh
rollup -c
```

### 合并app.js和库文件

```sh
gulp build:js
```

### 清空输出文件

```sh
npm run clear
```

### 一键打包（打包app.js，合并app.js和库文件组合命令）

```sh
npm run build
```

### 部署

```sh
npm run deploy
```

### 一键打包构建部署

```sh
npm run doall
```