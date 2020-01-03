比较修改内容
===========

## 知识点

* git diff [--cached]

## 实战演习

~~~bash
$ nano index.htm
...
...
#工作文件夹比较
$ git diff
#把修改文件追加到索引区
$ git add index.htm
#无法比较工作文件夹的修改文件
$ git diff
#索引区比较
$ git diff --cached
~~~

## 课程文件

https://github.com/komavideo/LearnGit

## 小马视频频道

http://komavideo.com
