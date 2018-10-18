---
title: hexo学习
date: 2018-10-16 22:44:39
tags: [hexo,博客,node.js]
---

## hexo学习

### node.js安装 

之前已经安装过node.js。

不过node.js版本有点旧，是4.x 版本，需要升级，所以安装了node.js的版本管理器 nvm

需要执行的命令（只是安装版本管理工具，还没有实现安装最新稳定版本的node.js）

``` bash
$ npm install -g n
```

然后再安装稳定版的node.js

``` bash
sudo n stable
```

### npm安装hexo

``` bash
npm install hexo-cli -g
```

### 创建站点

进入某个目录（具体实验是在~/Sites/hexo），执行

``` bash
$ hexo init blog
```

然后就可以本地启动 

``` bash
$ hexo server
```

默认是监听4000端口，然后访问localhost:4000 能够看到默认主题和hello world的博文。
