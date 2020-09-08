# 2312
mkdir  directory    #建立Git仓库

git init     #初始化Git仓库

git add    #保存的暂存区

git commit -m "解释说明"   #提交到Git版本库

git status    #Git当前状态

git log     #Git提交的历史记录

git reset --hard HEAD^（或者commit 前五位）   #Git会退到上一版本

git reflog    #记录Git执行的历史命令

git diff HEAD -- file    #查看工作区和版本库的区别

git checkout -- file    #撤销对工作区的修改

git reset HEAD file    #撤销对暂存区的修改

git rm file    #确定删除版本库的文件

git remote add origin git@gitlab.com:用户名/仓库名称    #关联远程仓库

git push -u origin master    #推送master分支到远程仓库并合并本地和远程master

git push origin master    #提交master分支到远程仓库

git clone git@gitlab.com:用户名/仓库名称

git branch    #查看分支

git branch <name>    #创建分支

git checkout <name>    #切换分支

git checkout -b <name>    #创建并切换分支

git merge <name>    #合并分支到当前分支

git branch -d <name>    #删除分支

git log --graph --pretty=oneline --abbrev-commit    #查看分支合并图
