Git忽略管理
==========

设置Git忽略的文件，这些文件不参与Git库的提交和管理。（例如：Node.js的[node_modules]文件夹）

## 知识点

* .gitignore

帮助网页:

https://git-scm.com/docs/gitignore

## 实战演习

~~~bash
$ nano test.tmp
...
$ git status
$ nano .gitignore
...
*.tmp
...
$ git status
$ mkdir subdir
$ nano subdir/my.css
...
$ git status
$ nano subdir/my.tmp
...
$ git status
~~~

## 课程文件

https://github.com/komavideo/LearnGit

## 小马视频频道

http://komavideo.com
