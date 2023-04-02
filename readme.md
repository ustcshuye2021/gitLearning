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

将生成的 `id_rsa.pub` 文件里面的内容复制，粘贴到 Github 用户设置里面关于 SSH keys 的部分

就可以克隆、推送自己的仓库了
