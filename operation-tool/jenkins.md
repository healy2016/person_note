Jenkins是一个开源软件项目，是基于Java开发的一种持续集成工具，用于监控持续重复的工作，旨在提供一个开放易用的软件平台，使软件的持续集成变成可能。
#### 1.下载地址
> * https://jenkins.io/download/

#### 2.windows 安装
> * 下载对应的window版本，如jenkins-2.73.3.zip
> * 解压出jenkins.war包
> * 到其根目录执行：java -jar jenkins.war

#### 3.windows 访问地址
> * http://localhost:8080

#### 4.注意
> * 本地必须配置好java的环境变量
> * 此版本必须会用jdk1.8或者以上

#### 5.端口被占用
> * 启动时:java -jar jenkins.war --httpPort=1080

#### 6.web端的配置和API的使用

#### 7.FAQ

#####1)Jenkins中无法启动子进程的解决办法
> * Q:Process leaked file descriptors. See http://wiki.hudson-ci.org/display/HUDSON/Spawning+processes+from+build for more information

> * 启动时添加禁用参数
> * java -Dhudson.util.ProcessTree.disable=true -jar jenkins.war  

