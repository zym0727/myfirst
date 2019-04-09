自己的mysql数据备份
git init 初始化
git add .将所有文件添加到仓库  git add添加到库
git commit -m "提交注释" 
git remote add origin https/git 添加远程仓库的关联
git pull --rebase origin master  代码合并pull=fetch+merge
git push origin master 将当前分支推送到origin主机的对应分支。
git push -u origin master 当前分支与多个主机存在追踪关系，那么这个时候-u选项会指定一个默认主机，这样后面就可以不加任何参数使用git push。