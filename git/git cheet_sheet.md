

+ 新增遠端資料庫
```sh
git remote add 
```

+ 設定遠端repository

```sh
git remote add <repo-name> <repo-URL>
```

+ 針對單一分支設定upstream

```sh
git branch -u <remote-upstream>
```

+ 合併不相關的兩個分支

```sh
git pull <remote repo> <branch name> --allow-unreleated-history
```

+ push到指定的分支

```sh
git push <repository alias> <branch name>
```

+ 查看本地分支對應的遠端分支
```sh
git branch -vv
```

## Reference

[解决"requested upstream branch 'origin/master' does not exist"_set upstream to时报错 does not exists-CSDN博客](https://blog.csdn.net/jack22001/article/details/87946037)

[Git远程：分支的upstream_查看git branch的upstream-CSDN博客](https://blog.csdn.net/GarfieldEr007/article/details/88652243)