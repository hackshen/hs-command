# Git 常用命令

> demo-branch: 演示分支


#### 分支相关

```bash
# 切换分支
git checkout demo-branch

# 创建新分支并切换到该分支
git checkout -b demo-branch

# 删除本地分支
git branch -D demo-branch 

# 删除远程分支
1、git push origin -d demo-branch
2、git push origin :demo-branch

# 显示本地分支
git branch

# 显示远程分支
git branch -r

# 显示本地和远程分支
git branch -a

# 显示本地分支关联远程仓库情况
git branch -vv

# 重命名本地分支
git branch -m new-branch


```
#### 拉取远程仓库代码到本地

```bash
# 拉取远程仓库代码到本地当前分支(本地分支已与远程分支关联)
git pull

# 拉取远程仓库代码到本地其它分支
git pull <remote-branch>:<local-branch>

# 
```

