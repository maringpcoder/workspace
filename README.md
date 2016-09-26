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

