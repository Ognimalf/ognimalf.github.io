### Git 基本操作

作为初学者,在这里列举一些常用的git命令,以便随时查阅  

1. `git init` 初始化当前文件夹,创建本地仓库
2. `git config user.name` , `git config user.email` 查看git账号的用户名与email地址
3. `git config --global user.name xxxxx` , `git config --global user.email xxxxx@xx.xxx` 修改git账号的用户名与email
4. `git clone https/ssh` 从github上克隆仓库
5. `git add` 可以将文件添加到暂存区, `git add .` 将所有文件添加到暂存区, 添加后可以用`git status -s` 查看文件
6. `git commit` 提交最新的代码, 可用选项 `-a` 能够提交修改过的文件并提交
7. `git push` 将本地分支上传到远程并合并 
   `git push origin master` 将本地分支上传到origin主机的master分支