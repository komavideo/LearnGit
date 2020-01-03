使用Tag标签
==========

## 知识点

* 系统版本号管理
* git tag [tag_name] [commit_id]
* git show [tag_name]
* git tag -d [tag_name]

### 系统版本号管理

任何软件系统，应用程序在发布时都应该给一个版本号，来管理每次发布的内容，便于今后的管理。

例如：

1.1.4

NNN.abc.xxx

* NNN:大版本号
* abc:每次做出的小更新时，发布的版本号
* xxx:每次bug修正时发布的版本号

## 实战演习

~~~bash
$ git tag
$ git tag v1.0.0
$ git tag
$ nano index.htm
...
#修正bug1
...
$ git add .
$ git commit -m "fixed bug1."
$ git tag v1.0.1
$ git tag
$ nano index.htm
...
#修正bug2
...
$ git add .
$ git commit -m "fixed bug2."
$ git tag v1.0.2
$ git tag
$ nano index.htm
...
#新功能追加
...
$ git add .
$ git commit -m "added feature1."
$ git tag v1.1.0
$ git tag
$ git show v1.0.1
$ git show v1.0.2
~~~

## 课程文件

https://github.com/komavideo/LearnGit

## 小马视频频道

http://komavideo.com
