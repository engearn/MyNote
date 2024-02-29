1.使用 git init 命令建立版本库;
2.使用 git add * 命令将更新的文件从 工作区 加入版本库 缓存区;
3.使用 git commit -m "更新内容" 命令进行 Commit,将更新内容从 暂存区 加入到 本地库，每一次 Commit 就相当于保存一份备份, 作为时间线的一个节点;
4.使用 git log 命令查看完整时间线, 方便进行版本回退;
5.使用 git reset --hard <commit_id> 进行版本回退, 即返回你保存的某个备份, <commit_id> 是你使用 git log 看见的 ID 值;
6.如何使用 Git 将本地的版本库推送到 GitHub;
7.使用 git clone <url> 命令将 远程库 上的代码仓库给 Clone 到本地库.
8.使用 git pull 拉取远程分支(团队其他人可能修改了代码), 如果有冲突, 解决冲突;
9.使用 git push 推送本地库到远程库，本地分支到远程分支, 进行团队同步;
