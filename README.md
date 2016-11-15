# laravel
使用gitbook记录笔记

学习网站:

[laravel-china](https://laravel-china.org/)
[laravist](https://laravist.com)
[laracasts](https://laracasts.com)

## gitbook记录笔记
>gitbook是基于node.js的命令行工具，需先安装node，再通过npm安装

    1. 在github上建立一个仓库
    2. 登录gitbook,用github账号登录，选择创建的git仓库
    
## gitbook笔记修改

安装gitbook命令行工具及相关差价

        npm install -g gitbook-cli
        gitbook install

创建SUMMARY.md文件（用于目录生成）

        生成目录
        gitbook init 

启动gitbook服务器，会生成一个localhost:4000的端口，即可实时预览

## 上传本地更细

        git commit -a -m 'editor'
        git push