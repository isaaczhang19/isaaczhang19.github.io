
# This branch is source code for hexo to generate static web hosted on master

## Working in a new enviroment

```bash
git clone https://github.com/isaaczhang19/isaaczhang19.github.io.git isaaczhang19
cd isaaczhang19
npm install hexo
npm install hexo-deployer-git -save
```

## work on hexo

1. 通过`hexo new post_name`命令，会自动在`source/_post`目录下生成一个待写的`post_name.md`文件
2. 编写完该md文件后，用`hexo generate`编译生成对应的HTML文件
3. 发布之前，可以用`hexo s`本地预览，然后通过`hexo deploy`发布到远程仓库的`master`分支，然后你的个人站点就能看到刚才新加的文章了
