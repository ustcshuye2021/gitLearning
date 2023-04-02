关于 Git 和 GitHub 使用的基础教程

https://www.cnblogs.com/schaepher/p/5561193.html

[Git教程 - 廖雪峰的官方网站 (liaoxuefeng.com)](https://www.liaoxuefeng.com/wiki/896043488029600)



在使用 git commit 提交信息之前，先设置名字和邮箱

```shell
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```


在新的电脑上关联 Github 账号

```shell
ssh-keygen -t rsa -C "youremail@example.com"
```

将生成的 `id_rsa.pub` 文件里面的内容复制，粘贴到 Github 用户设置里面关于 SSH keys 的部分，就可以克隆、推送自己的仓库了



往 GitHub 上分享

1. 在 GitHub 网站上 New Repository 新建仓库

2. 复制 SSH，在 `D:\repository` 文件中右键选择 `Git Bash Here` 输入 `git clone 复制的SSH`

3. 本地对内容进行增删以后输入以下命令把本地仓库同步到 GitHub 上

   ```shell
   git add -A
   git commit -m "xxx"
   git push
   ```

   
