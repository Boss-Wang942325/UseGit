/*	Git是目前世界上最先进的分布式版本控制系统
	Git is a distributed version control system.
	Git is free software distributed under the GPL.
	因为我们创建Git版本库时，Git自动为我们创建了唯一一个master分支
	所以，现在，git commit就是往master分支上提交更改。
	工作区 版本库(暂存区 master HEAD)
	git 跟踪的是修改
	
	指令
	
	git config --global user.name "Your name"
	git config --global user.email "email@example.com"
				注意git config命令的--global参数
				用了这个参数，表示你这台机器上所有的Git仓库都会使用这个配置
				当然也可以对某个仓库指定不同的用户名和Email地址
	
	mkfir name		创建文件夹
	pwd				显示当前目录
	git init		将这个目录变成git可管理的仓库(初始化)
	ls -ah			显示.git文件
	git add name	添加		把文件修改添加到暂存区
	git commit -m ""提交完成	把暂存区的所有内容提交到当前分支
	git status		掌握仓库当前的状态
	git diff		查看做了什么修改
	git log			查看提交日志
	git log --pretty=oneline
	git reflog		记录每一次命令
	git reset --hard HEAD^	版本回退
	git reset --hard 123a	进入指定版本
	git checkout -- file	撤销工作区的修改
	git reset -- file		撤销暂存区的修改
	rm         				删除工作区的修改
	git rm					删除暂存区的修改
*/
	