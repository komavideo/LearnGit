第一次提交(commit)
==========

## 知识点

* 建立文件（本地工作文件夹）
* 追加文件（索引区）
* 提交文件（本地库）

## 实战演习

~~~bash
$ mkdir myweb
$ cd myweb
#建立本地Git库
$ git init
#编辑(修改)本地文件
$ nano index.htm
...
...
#本地工作文件夹状态确认
$ git status
$ git add index.htm
#本地工作文件夹状态再次确认
$ git status
#将索引区内容提交本地库
$ git commit -m "created index.htm"
#查看提交历史
$ git log
~~~

## 课程文件

https://github.com/komavideo/LearnGit

## 小马视频频道

http://komavideo.com
