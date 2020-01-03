制造分支冲突
===========

当团队中多人同时编辑一个文件的时候，难免会出现源代码的编辑合并冲突的问题，那么我们该怎么解决呢？

## 知识点

* 做一个源代码冲突的场景
* git checkout -b [branch_name]

## 实战演习

~~~bash
$ git checkout -b dev
$ nano index.htm
...
$ git add .
$ git commit m "modified by dev."
$ git checkout master
$ nano index.htm
...
$ git add .
$ git commit -m "modified by master."
$ git branch
$ git merge dev
#出现源代码版本冲突，需要手动进行合并解决
~~~

## 课程文件

https://github.com/komavideo/LearnGit

## 小马视频频道

http://komavideo.com
