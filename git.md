# git 基本使用

### git拉取更新

自动合并

```bash
git pull origin main
```

不自动合并

```bash
git fetch origin
git merge origin/main
```

### git删除文件

```bash
git rm -r -f dir
#递归向下删除文件夹
git clean -fd	
#清除空文件
git mv src_file dst_file
#移动文件
```

