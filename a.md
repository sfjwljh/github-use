1. 到目标目录下右键，git bash here
1. 配置用户信息
>git config --global user.name xxx
>git config --global user.email xxx@xxx
* push常见用法
  * 一般格式：git push <远程主机名> <本地分支名> <远程分支名>
  * 完整：git push origin main:refs\for\main
  * git push origin main 省略了远程分支，默认和本地同名
  * git push origin : refs/for/master 省略了本地分支，等同将一个空分支push，等于删除远程分支，即git push origin --delete master
  * git push origin，如果当前分支和远程分支存在追踪关系，那么都能省略
  * git push，如果当前只有一个远程分支，那么远程主机名也能省略 
  * git push -u origin main ,当前分支和多个主机有跟踪关系，-u指定一个默认主机，这样以后就可以不加任何参数直接git push
  * 
1. 跟着github教程试试
>git init
>git add README.md
>git commit -m "first commit"
>git branch -M main
>git remote add origin http://github.com/xfjwljh/github-use.git
> git push -u origin main


