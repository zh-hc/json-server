# json-server

本地数据接口

参考链接：<https://blog.csdn.net/zsl15039718107/article/details/106837370>

## 全局安装

```bash
npm install -g json-server
```

## 在单个项目文件中安装

```bash
npm install
npm install json-server -S
npm init --yes
```

## 在package.json文件中的操作

修改scripts中配置如下：

```js
"scripts": {
    "json-server": "json-server --watch db.json",
    "json:server:remote":"json-server http://jsonplaceholder.typicode.com/db"
  },
```

## 创建json文件

注意：创建的json文件名要与上面scripts中修改的–watch 后面的文件名保持一致。

## 在创建的json文件中写入需要的数据

## 启动

```bash
npm run json-server
```
