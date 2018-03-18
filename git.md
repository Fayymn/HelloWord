- 打开Git

右键-> gitbash here

- 关联远程仓库

```
git init # 初始化本地仓库 创建 .git 文件夹
git remote add origin git@server-name:path/repo.git # 关联远程仓库
```

- 拉取


```
git pull origin master # 拉取origin仓库的master分支
``` 

- 推送

```
git add . # 添加当前文件夹所有修改
git commit -m 'content' # 提交已添加的修改 并附以注释
git push origin master # 推送到远程origin仓库的master分支
```
