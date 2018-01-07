Git使用指南

>* git init
>* git add README.md
>* git commit -m "first commit"
>* git remote add origin  
>* git@github.com:healy2016/healy2016.github.io.git
>* git push -u origin master  （提交到主分支中）



FAQ：
####1
>* Q:Could not open a connection to your authentication agent
>* A:ssh-agent bash

####2
>* Q:github提示Permission denied (publickey)
>* A:  
  
  1) ssh-keygen -t rsa  
  2) 一路回车...  
  3) 在GitHub中添加ssh key，title自己命名即可，key就是刚才生成的文件内容  
  4) ssh-add id_rsa.pub （这个是生成的文件名） 在git中执行即可

