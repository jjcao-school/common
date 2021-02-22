# Git
- 一个面向开源及私有软件项目的托管平台，是一个分布式的版本控制软件，它可以有效、高速地处理各种项目的版本管理。[git - 简明指南](http://rogerdudler.github.io/git-guide/index.zh.html)
- [Git Overview](https://cs.brown.edu/courses/csci0060/assets/slides/slides12.pdf): A lecture slides on git for a comprehensive overview on what git is!
<!-- - [廖雪峰Git教程](https://www.liaoxuefeng.com/wiki/896043488029600) 
- [Git菜鸟教程](https://www.runoob.com/git/git-tutorial.html) -->

## GitHub
> Visual Studio Code等IDE可以满足日常github使用，配合shell command, 不安转github的第三方GUI也可以。
- Git 的一个托管平台（把本地的代码历史上传到云端），相对于传统的 SVN( Subversion )，GitHub 具有更强大的功能，已成为当前人们用来管理代码及各种文档的利器。
官方教程：[https://lab.github.com/](https://lab.github.com/) 

## GitHub Desktop
> [官网](https://desktop.github.com/)，[官方文档](https://help.github.com/en/desktop)
- GitHub 的客户端（桌面端）软件 ，它与 GitHub 进行在线同步，可简化 Git 与 GitHub 间的操作，是 Git 功能的简单封装。可以完成一般的操作，但复杂的操作就只能使用 Git 的命令行。推荐使用！
- 必须学会**冲突**的解决（在 merge 其他分支到 `master` 分支的时候很容易产生冲突）

## Git 常用命令
另外，建议学会以下几个重要的命令
- `git log`：查看历史版本信息
- `git reset --soft <hash-code>`：跳转到任意版本，保留代码不变
- `git reset --hard <hash-code>`：跳转到任意版本，代码改变，谨慎使用
- `git push origin master -f`：当将本地代码推到 GitHub 后还想撤销时，先本地回退到相应版本，然后用此命令将本地版本强推到 GitHub 上






