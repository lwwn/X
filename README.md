这是一个散漫的地方 , 真的很散漫~
git 
下载地址：
https://git-scm.com/downloads
配置环境变量
我的电脑> 属性> 高级系统设置>环境变量> 系统环境变量 > path > 编辑 > 把git 路径复制进去>D:\git\Git\cmd> 保存
配置username os password 
git config  --global user.name "lwwn"
git config  --global user.email "365177686@qq.com"
查看账号
git config --get user.name
git config --git user.email 

克隆一个项目 
git clone  仓库地址
查看本地分支  或者仓库分支
git branch  本地  git branch -a   远程仓库分支
查看远程仓库地址
git  remote -v
