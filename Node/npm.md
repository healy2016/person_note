### 查看全局所有的依赖，一级目录下
> * npm list -g --depth 0

### 开发环境下的依赖安装
> * npm install XXX --save-dev

### 生产环境下的依赖安装
> * npm install XXX --save

### 使用淘宝镜像的安装方法
> * npm --registry https://registry.npm.taobao.org install express

### 安装cnpm直接使用淘宝镜像：必须是全局安装-g
> * npm --registry https://registry.npm.taobao.org install -g cnpm

### 清空缓存
> * npm cache verify

### gitbook编译路径输出
> * gitbook build --output=/tmp/gitbook

### pm2 部署工具
> * pm2 start [apppath]

### pm2 查看所有列表
> * pm2 list

### pm2 重启，停止
> * pm2 stop [name]   \   pm2 restart [name]

FAQ：
### 问题1
![](/assets/QQ图片20171214185706.png)
> * npm cache verify
> * cnpm install xxx --save
> * 执行以上两步即可

