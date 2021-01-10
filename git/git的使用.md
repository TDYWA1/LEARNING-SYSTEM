# git的使用 
---
---
## 1. git config
- 全局设置
		git config user.name
		git config user.email

---
- 初始化
		git init
---
- 添加到缓存区
		git add filename
---
- 提交
		git commit -m "descrip"
---
- 放弃修改
		git checkout -- filename
		git reset HEAD filename
---
- 回退
		git reset --hard sha1/HEAD^
---
- 查看历史
		git log --pretty=oneline
		git reflog
---
- 添加远程仓库
		git remote add origin 
---
- 推送到远程仓库
		git push origin master
