# Git_quickuse

## 1. 创建版本库

```
git init
```

##连接到远程仓库

```
git remote add <remote-name> <remote-url>
```
###如果连接不上

```
unable to access 'https://github.com/Orign-al/STM32H743VIT6_CODE.git/': OpenSSL SSL_connect: SSL_ERROR_SYSCALL in connection to github.com:443

```

```
https://blog.csdn.net/qq_43546721/article/details/139506583
```

##更改由于main和master问题导致的上传失败

```
https://blog.csdn.net/mo_sss/article/details/137927136
```

## 2. 添加文件到暂存区

```
git add 文件名
```

## 3. 提交暂存区到版本库

```
git commit -m "提交说明"
```

## 4. 查看状态

```
git status
```

## 5. 查看提交历史

```
git log
```


---
---
---
---
---
---
---
---
---


## 6、清除所有已缓存文件
你可以通过以下命令将所有已经缓存但未提交的文件移除：


```
git rm -r --cached .

```


## 6、让 Git LFS 跟踪这些大文件
你可以通过以下命令将所有已经缓存但未提交的文件移除：


```
git lfs install
git lfs track "*.mp4"
git add .gitattributes
git add .
git commit -m "Use Git LFS for large files"
git push origin master


```



```
git rm --cached "文件路径"
git commit -m "Remove large files"
git push origin master



```


---
---
---
---
---
---
---
---
---

## 6. 回退版本

1. 回退到上一个版本

```
git reset --hard HEAD^
```

2. 回退到指定版本

```
git reset --hard 版本号
```

## 7. 克隆版本库

```
git clone 版本库地址
```

## 8. 推送到远程版本库

```
git push
```

## 9. 从远程版本库拉取代码

```
git pull
``` 

## 10. 创建分支

```
git branch 分支名
```

## 11. 切换分支

```
git checkout 分支名
```

## 12. 合并分支

```
git merge 分支名
```

## 13. 删除分支

```
git branch -d 分支名
``` 

## 14. 解决冲突

```
git mergetool
``` 

## 15. 取消暂存区文件

```
git reset HEAD 文件名
``` 

## 16. 取消本地修改

```
git checkout -- 文件名
``` 

## 17. 取消远程修改

```
git reset --hard origin/分支名
``` 

## 18. 同步远程分支

```
git fetch origin 分支名:本地分支名
``` 

## 19. 推送本地分支到远程分支

```
git push origin 分支名
``` 

## 20. 推送本地分支到远程分支并设置upstream

```
git push -u origin 分支名
``` 

## 21. 克隆远程版本库

```
git clone 版本库地址
``` 

## 22. 克隆远程版本库到指定目录

```
git clone 版本库地址 目录名
``` 

## 23. 克隆指定分支

```
git clone -b 分支名 版本库地址
``` 

