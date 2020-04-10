
## Hugo 搭建个人博客
---
之前曾尝试基于nodejs的hexo创建博客([我的hexo博客](https://gerogeliu.github.io))，
使用hexo博客框架搭建博客非常简单，只需要会一些简单的markdown语法就ok啦。

---

现在，尝试使用另一个基于go语言的搭建博客的框架Hugo，据说很好用。。


## 过程记录

- 下载安装hugo
```sh
#macos
$ brew install hugo
```
window系统，可以点击[链接](https://github.com/gohugoio/hugo/release)下载相应版本的hugo，安装后进入下一步

- 验证是否正确安装
```sh
$ hugo version
output: Hugo Static Site Generator v0.68.3/extended darwin/amd64 BuildDate: unknown
```
- 初始化博客
```sh
#新建myblog目录并创建必要的文件
$ hugo new site myblog
```

- 挑选博客主题，点击[挑选主题](https://themes.gohugo.io/)，选择合适的主题，下载到本地
```sh
#挑选好的主题，下载到本地
$ git submodule add https://github.com/alex-shpak/hugo-book themes/book
```

