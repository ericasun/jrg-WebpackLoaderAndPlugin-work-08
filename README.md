# 08实现一个Webpack Loader——my-html-loader
实现一个html-loader，当检查到加载的文件是以.html为后缀，就使用我们的my-html-loader进行编译

## 代码路径
loaders/my-html-loader.js

# Project setup
```
npm install
```

# 编译
```
npm run  build
```

# 展示
```
cd dist

http-server -c-l
```
http://127.0.0.1:8080/my.html


# 自动部署
```
sh ./deploy.sh
```

  