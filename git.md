# git分支切换
### 1、git checkout -b dev
### 2、git branch dev
###  git checkout dev
### 3、git switch -c dev
### 直接切换到master： git switch master

# git 合并分支
### git merge dev //将dev分支当前分支合并到master



# git查看分支
### git branch

# 本地添加远程库
## 关联前需要初始化仓库
### git init
## 关联一个远程库
### git remote add origin git@github.com:tanatc/项目名.git  
## 关联多个远程库
### git remote add github git@github.com:tanatc/项目名.git  
### git remote add gitee git@github.com:tanatc/项目名.git
## 多个远程库推送
### git push github master
### git push gitee master

# 删除关联
### git remote rm origin

# 查看远程库信息
### git remote -v


