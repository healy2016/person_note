# 二、快速入门

### supervisor监控的热部署问题
> * --监测路径（相对路径很重要）


### node-inspect + NIM debugger调试node

> * node-pre-gyp ERR! Tried to download: https://node-inspector.s3.amazonaws.com/debug/v0.4.6/node-v46-linux-x64.tar.gz 
node-pre-gyp ERR! Pre-built binaries not found for v8-debug@0.4.6 and node@4.4.5 (node-v46 ABI) (falling back to source compile with node-gyp)

> * node v8.x以上安装 npm install --global node-inspect 会报以上错误

![](/assets/QQ图片20171204124646.png)

> * 百度结果：版本对应报错，可以先降级到node v6.9，装完后升回原版本。

> * node --inspect server.js 启动服务

