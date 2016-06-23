$ mkdir git
$ cd git
$ pwd
$ git init
//创建文件
$ git add new.txt
$ git commit -m "explain"

$ git log

$ git reflog

$ git reset --hard HEAD^

//撤销工作区的修改
$ git checkout -- readme.txt
$ git reset HEAD readme.txt

$ git remote add name address
$ git push -u origin master
$ git push origin master
