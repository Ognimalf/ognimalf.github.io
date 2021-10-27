### Git 基本操作

作为初学者,在这里列举一些常用的git命令,以便随时查阅  

1. `git init` 初始化当前文件夹,创建本地仓库
2. `git config user.name` , `git config user.email` 查看git账号的用户名与email地址
3. `git config --global user.name xxxxx` , `git config --global user.email xxxxx@xx.xxx` 修改git账号的用户名与email
4. `git clone https/ssh` 从github上克隆仓库
5. `git add` 可以将文件添加到暂存区, `git add .` 将所有文件添加到暂存区, 添加后可以用`git status -s` 查看文件
6. `git rm --cache FILE` 删除暂存区文件
7. `git commit` 提交最新的代码, 可用选项 `-a` 能够提交修改过的文件并提交
8. `git log` 可以查看commit的历史
9. `git rebase` 在commit之后,最新的提交并不与远程的分支相同,此时需要合并commit
10. `git pull` 在`git commit`之后如果直接push操作可能导致失败,因为本地仓库落后于远程仓库,因此我们需要先将远程的分支抓取过来
11. `git push` 将本地分支上传到远程并合并 
   `git push origin master` 将本地分支上传到origin主机的master分支