使用分支
========

Git分支功能对于项目开发中的团队合作有着非常重要的作用，同时对于生产环境的更新管理也起着不可替代的作用，是Git最重要的功能。

在项目开始前，应该首先对Git分支的管理有一个明确地规划，明确每个分支的功能和担当者，这样才会保证项目正常推进，不至于陷入混乱。

## 知识点

* git branch [name]
* git checkout branch_name

## 实战演习

~~~bash
$ git branch
$ git branch dev
$ git checkout dev
$ nano style.css
...
$ git add .
$ git commit -m "modified style.css."
$ git log
$ git checkout master
$ git log
~~~

## 课程文件

https://github.com/komavideo/LearnGit

## 小马视频频道

http://komavideo.com
