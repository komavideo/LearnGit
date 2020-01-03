更新最后的提交
============

## 知识点

* git commit -m "commit message"
* git commit --amend
* git commit -am "commit message" [--amend]

## 实战演习

~~~bash
$ nano index.htm
...
$ git add .
$ git commit -m "modified."
$ git log
# remove debug info.
$ nano index.htm
...
$ git add .
$ git commit --amend
$ git status
$ git log
~~~

## 课程文件

https://github.com/komavideo/LearnGit

## 小马视频频道

http://komavideo.com
