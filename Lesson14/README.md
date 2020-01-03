合并分支
=======

## 知识点

* git merge
* git branch -d [name]

## 实战演习

~~~bash
$ git branch
$ git checkout dev
$ nano index.htm
...
$ git add .
$ git commit -m "modified1."
$ git log
$ git branch
$ git checkout master
$ git log
$ git branch
$ git merge dev
$ git log
$ git branch -d dev
$ git branch
~~~

## 课程文件

https://github.com/komavideo/LearnGit

## 小马视频频道

http://komavideo.com
