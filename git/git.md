### Git 常用命令
| 命令名称 | 作用 |
| ---     |  --- |
|git config --global user.name 用户名| 设置用户签名|
|git config --global user.email 用户邮箱| 设置用户邮箱 |
|**git init** | 初始化本地库 |
|**git status**| 查看git的状态 |
|**git reflog**| 查看git提交的历史版本|
|git log|查看git提交的详细版本日志|
|**git add 文件名**| 将文件添加到暂存区|
|**git commit -m "日志信息" 文件名**| 将文件提交到本地仓库|
|**git reset --hard 版本号**|版本穿梭|
|git restore --staged | 将暂存区的文件从暂存区撤出，但不会更改文件|

### Git 分支操作
|命令名称| 作用 |
| --- | --- |
| git branch 分支名 | 创建分支 |
| git branch -v | 查看分支 |
| git checkout 分支名 | 切换分支 |
| git merge 分支名 | 将指定的分支合并到当前分支 |

### Git远程操作
|命令名称| 作用 |
| --- | --- |
| git remote -v|查看当前所有远程地址别名|
|git remote add 别名 远程地址| 起别名 |
| git push 别名 分支 | 推送本地分支上的内容到远程仓库|
|git clone 远程地址 | 将远程仓库的内容克隆到本地 |
| git pull 远程仓库地址别名 远程分支名|将远程仓库对于分支最新内容拉下来后与当前本地分支直接合并|


