learn_git
=========

学习git的基本操作，学习常用命令
git init 
git clone 
git log 
git commit 
git add

创建一个远程分支

git push origin 分支名


git push <远程主机名> <本地分支>:<远程分支>

git pull <远程主机名> <远程分支>:<本地分支>

git clone 会确定本地master 分支 跟踪 origin/master分支
手动可以建立本地分支与远程分支的关系 
git branch --set-upstream master origin/next  创建本地分支master与远程分支下的next分支进行跟踪
