## 初始化
空文件就 git init

## git配置

git config global user.name "git的name"
git config global user.email "github使用的邮箱"

## 生成ssh密钥

## 提交请求信息
git add [文件名]
git add把文件添加进去，实际上就是把文件修改添加到暂存区

git commit -m "提交信息"
git commit提交更改，实际上就是把暂存区的所有内容提交到当前分支
## 退回之前的

git reset --hard 


## 添加到远程仓库GitHub

添加远程仓库
git remote add origin git@github.com:GitHub名字/项目的名字.git

把暂存区代码推送到远程仓库去
git push -u origin master

## 统一分支

github上分支是main，而本地的默认分支是master，让我误以本地代码为没有推送到GitHub

然后 git push -u origin main 结果报错，因为我没有本地分支main

git checkout -b main

使用 git checkout -b main 在git工具上创建main分支并进入

git branch -D master 

删除本地的master分支

git push origin --delete master 

删除GitHub项目的master分支

git push -u origin main       统一使用main分支

