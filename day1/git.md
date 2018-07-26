   day1
1.git  项目管理工具，管理项目代码
2.vue 框架 ****
3.webpack  打包神器
 
GIT

#安装

下载地址：https://git-scm.com/
在cmd中输入git,验证是否安装成功
git --version  版本号

##代码管理
1.本地仓库
  
2.远端仓库
  	1.github  https://github.com/开源（分享代码）
     	账号：renxiaoyao1 邮箱：1615130433@qq.com
	

  2.gitlab  分享开源 管理系统 他也是网站管理界面——公司用的  需要安装

###创建git仓库
	1.Public 开源（任何人都可以来下载你的代码），	开源相当于对编程做了贡献
	2.Private 私有（只有你个人拥有的 除了自己以外		任何人都不能下载）是需要付费的

##使用git
1.直接在本地初始化项目 开始开发项目
2.直接clone远程仓库开始研发项目

##配置git用户一台电脑只用配置一次
1.git config --global user.name"renxiaoyao1"
2.git config --global user.email"1615130433@qq.com"

###01
1.init  初始化本地项目的仓库
	git init 

2.add 用于添加现有项目的文件添加至本地仓库（版本之间的切换）.英文输入法局号点，代表根目录
	git add<filename>
	git add app.js
	添加所有文件
	git add .(没有任何反馈)

3.commit 提交暂存版本（相当于备份）
	git commit -m "描述信息"
	git commit -m "first init commit"

4.remote add
remote add 用来添加远程仓库地址到本地仓库,没有反馈
	git remote add<别名><远程仓库地址>
	git@github.com:renxiaoyao1/renxiaoyao.git
5.push
push 用于把本地仓库的代码同步到远程仓库，前提是通过remote add 添加了仓库才行
	git push <别名> 主分支
	git push github master
也可以使用-u指令绑定，到push命令
	git push -u github master
使用了-u绑定之后以后都不需要使用别名进行push
	git push
	输入账号和密码
	输入密码是看不见密码的输入的
	默认空文件夹是不会被上传的

 
 