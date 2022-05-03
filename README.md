# my-vue-library

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

peerDependencies: 依赖于外部包，本地不用下
发布流程：https://blog.csdn.net/qq_41887214/article/details/120491173
npm run start:会生成lib，npm link会生成本地预览的链接，其他项目通过npm link [packageName] 来访问当前的组件
npm run buildPublish:发布包