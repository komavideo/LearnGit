返回过去2
========

## 知识点

* git reflog [-n num]
* git reset --hard [commit_id]

## 实战演习

返回过去之后，通过git reflog命令找到现在的位置（commit_id），再从过去返回回来。

~~~bash
$ git log
$ git reset --hard HEAD~2
$ git reflog
* git reset --hard [commit_id]
~~~

## 课程文件

https://github.com/komavideo/LearnGit

## 小马视频频道

http://komavideo.com
