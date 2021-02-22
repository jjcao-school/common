# 软件使用说明

这里提供本课程中所使用的一些软件的简单介绍和使用说明等。

## GitHub [->](github.md)
本课程要求使用GitHub来管理和维护作业的代码，须设为私有库。

## Markdown language
> [Markdown Tutorial](https://www.markdowntutorial.com) 
- Typora是一个所见即所得的Markdown格式文本编辑器，支持Windows、macOS和GNU/Linux操作系统，用于浏览和编辑本地版的GitHub的`*.md`文件。
    - Typora：[官网](https://www.typora.io/)，[官方文档](http://support.typora.io/) 
    - Visual Studio Code等IDE 配合markdown插件，也可实时编辑+显示 md文件

### MathJax
文档中可能包含一些数学公式，GitHub 不支持直接显示数学公式，需要额外设置才能正常显示。
>
> 方法如下：
>
> - 网页端查看：Google Chrome 浏览器插件 [MathJax](https://chrome.google.com/webstore/detail/mathjax-plugin-for-github/ioemnmodlmafdkllaclgeombjnmnbima)（需要科学上网 fq），没法科学上网的同学参考 [Crx4Chrome | MathJax](https://www.crx4chrome.com/crx/72309/) 以及 [Chrome 插件离线安装方法](https://chromecj.com/utilities/2015-04/423.html) 
> - 本地查看：使用 Markdown 编辑器 Typora（[下载链接](https://www.typora.io/windows/typora-setup-x64.exe?)），需要手动打开“**内联公式**”功能（Typora 菜单 -> 偏好设置 -> Markdown -> Markdown 扩展语法 -> 勾选“内联公式”）

## Visual Studio Code
- Use [Visual Studio Code](https://code.visualstudio.com/docs/editor/debugging) as your IDE, and debugging with it.

## CMake

> [官网](https://cmake.org/)，[视频教程](https://www.bilibili.com/video/av85644125/)，[官方教程](https://cmake.org/cmake/help/latest/guide/tutorial/index.html)，[官方文档](https://cmake.org/documentation/), [简易说明](cmake.md)  

本课程要求使用 `CMake > 3.18.2` 版本来构建项目。CMake是众多开源项目采用的方式，如 [pbrt-v3](https://github.com/mmp/pbrt-v3) 。学会使用CMake，就能够很容易使用他人的开源项目。

CMake 是一个跨平台的安装（编译）工具，可以用简单的语句来描述所有平台的安装（编译过程），开发者通过编写一种与平台无关的 CMakeList.txt 文件来定制整个编译流程，然后再根据目标用户的平台进一步生成所需的本地化 Makefile 和工程文件。CMake能够有效地描述这些文件之间的依赖关系以及处理命令，当个别文件改动后仅执行必要的处理，而不必重复整个编译过程，可以大大提高软件开发的效率。

## C++
> [C语言菜鸟教程](https://www.runoob.com/cprogramming/c-tutorial.html), [C++菜鸟教程](https://www.runoob.com/cplusplus/cpp-tutorial.html), [tutorial](http://www.tutorialspoint.com/cplusplus/index.htm">C++/C) 

<!-- ## Matlab
[tutorial](http://cn.mathworks.com/help/index.html) -->

## Python
> [tutorial](http://www.w3cschool.cc/python/python-tutorial.html)
