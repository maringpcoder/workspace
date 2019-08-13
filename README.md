#git

全局配置

git config --global user.name “freephp“  #配置Git用户名

git config --global user.email "xxx@yungengxin.com" #配置email

查看当前分支状态:git status 

将修改加入到提交区:git add filepath/file

提交修改:git commit -m “change message

推送到远程:git push origin branch_name

6.撤销修改:git checkout -- path/filename

7.基于某分支创建分支:git branch branch_name

9.创建并切换分支到新建分支:git checkout -b dev

8.合并分支git merge --no-ff otherBranchName

--no-ff是关闭快速合并的选项，建议每次合并都要这样。

创建本地develop分支  并且关联到远程分支origin/develop   git checkout -b develop origin/develop

指定当前分支和远程分支之间的链接关系 git branch --set-upstream marin origin/marin  marin是本地分支，origin/marin是远程分支

删除分支：git push origin :zhengdiao  "zhengdiao" 远程分支名称

将本地分支推送到远程分支 如果远程分支不存在则会自动新建远程分支 ： git push origin marin:marin  marin是本地分支 远程分支是marin分支

修改远程分支 ： git remote set-url origin URL

怎么查看当前的git分支是基于哪个分支创建的 ：git reflog --date=local --all | grep 要查询的分支名称
