# test

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).



在C:\Users\User中的.npmrc文件中添加如下配置：
ELECTRON_MIRROR=https://npm.taobao.org/mirrors/electron/
ELECTRON_BUILDER_BINARIES_MIRROR=https://npm.taobao.org/mirrors/electron-builder-binaries/

新建electron+vue的项目流程：
vue create test
vue add electron-builder
npm run electron:serve
npm run electron:build
打包完成后找到test/dist_electron中的test Setup0.1.0.exe点击安装即可