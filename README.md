# Node.js Getting started

一个简单的使用 Express 4 的 Node.js 应用整合了Vue。
可以运行在 LeanEngine Node.js 运行时环境。

## DEMO
[demo live](https://nodevueleancloud.leanapp.cn/)

## 本地运行

首先确认本机已经安装 [Node.js](http://nodejs.org/) 运行环境和 [LeanCloud 命令行工具](https://www.leancloud.cn/docs/leanengine_cli.html)，然后执行下列指令：

```
$ git clone git@github.com:lenvonsam/lean-node-vue-exmaple.git
$ cd lean-node-vue-exmpale
```

安装依赖：

```
npm intall -g webpack
npm intall -g webpack-dev-server
npm install
```

关联应用：

```
lean app add origin <appId>
```

这里的 appId 填上你在 LeanCloud 上创建的某一应用的 appId 即可。origin 则有点像 Git 里的 remote 名称。
本应用的appId: zPvMhtIOa5ED5UrT9Te3xHty-gzGzoHsz

启动项目：

```
webpack
lean up
```

应用即可启动运行：[localhost:3000](http://localhost:3000)



