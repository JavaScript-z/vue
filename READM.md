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