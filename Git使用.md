# Git 使用

## Git 简介

git 是什么？

git 是目前世界上最先进的分布式版本控制系统

添加文件到 git 仓库需要两步

1. 使用命令 `git add <file> <file> ` 可以反复使用
2. 使用命令 `git commit -m <message>` 完成

掌握工作区的状态使用 `git status` 命令，使用 `git diff` 查看修改内容

`HEAD` 指向的版本是当前版本，因此 Git 允许我们在版本的历史之间穿梭，使用命令 `git reset --hard commit_id`  HEAD^ 代表上一个版本，上上个版本就是 HEAD^^ ，往上 100 个版本可以写 HEAD~100

使用 `git log` 查看提交历史

用 git reflog 查看命令历史

