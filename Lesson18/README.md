使用别名
=======

在Git中可以将经常使用的命令以别名缩写的方式简化使用。

## 知识点

* git config --global alias.[name] [command_name]

## 实战演习

~~~bash
#将checkout命令简化为co
$ git config --global alias.co checkout
#将branch命令简化为br
$ git config --global alias.br branch
#将commit命令简化为cm
$ git config --global alias.cm commit
#将status命令简化为st
$ git config --global alias.st status
$ git br
$ git co dev
$ git st
$ git config -l
~~~

当然这种别名的定义根据每个人的使用习惯不同而不同，也可以在项目开始前作为项目的统一规则制定下来，使每个项目开发成员都统一使用一套大家都认可的别名，这样提高项目组内部的沟通效率。

## 课程文件

https://github.com/komavideo/LearnGit

## 小马视频频道

http://komavideo.com
