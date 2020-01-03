玩转开源中国Gitee
================

本期课程为您讲解如何使用Git命令连接远程服务器，如果编写提交代码到服务器端，完成团队的协同开发。

## 知识点

* git clone [url]
* git remote -v
* git push [origin] [master]

## 操作步骤

1. git clone 把远程库克隆到本地文件夹
0. 编辑本地文件夹的文件
0. 提交编辑的文件到本地信息库(git add ./git commit)
0. 将本地库同步(sync)到远程Git服务器

## 实战演习

通过操作开源中国LearnOSC库，为您展示如何使用分支，如果提交代码，让您了解整个Git远程库的使用过程。

~~~bash
$ git clone https://gitee.com/komavideo/LearnOSC
$ cd LearnOSC
$ git status
$ git branch
$ git branch -a
$ git branch dev remotes/origin/dev
$ git branch
$ git checkout dev
$ git status
$ nano README.md
...
git config --global color.ui true
...
$ git add .
$ git commit -m "为初期设定增加color.ui选项"
$ git status
$ git remote -v
$ git push origin dev
~~~

## 课程文件

https://github.com/komavideo/LearnGit

## 小马视频频道

http://komavideo.com
