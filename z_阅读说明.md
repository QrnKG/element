# 使用
```
cnpm i  // 安装包
```
```
cnpm run dev // 运行
```
如无法运行，则修改代理ip 

修改 dev 脚本
```
    "dev": "npm run bootstrap && npm run build:file && cross-env NODE_ENV=development webpack-dev-server --config build/webpack.demo.js & node build/bin/template.js",

```
取消 `npm run bootstrap`
