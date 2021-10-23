# Git培训上：基础入门

## 课程介绍

### 内容概览

通过本次课程学习，各位同学可以学到基础的git操作，**能够达到的水平**：

1. **绝大部分**在项目中可能会用到的操作
2. 创建并维护**自己**的远程代码仓库
3. 创建并维护**小型**的合作项目
4. 更加舒适的在自己的工作环境（如vscode）中使用Git操作

为了帮助大家更好的掌握课程内容，我们在《Git培训下》结束后准备了一个**课程作业项目**，涵盖了本课程大部分内容，难度简易，希望同学们喜欢（微笑）。

### 先修知识

课程开始前，我们希望你知道：

1. 什么是Github
2. 怎么稳定地上Github
3. 怎么稳定地上Google
4. 什么是命令行
5. **我为什么要学Git**

以上问题除了第五条外，**均可通过百度、谷歌或者请教同学**获得答案。

（关于Git和GitHub的介绍，如果你想浅显的了解，我会建议你去看看廖雪峰老师的网站，说的很清楚。如果你是顶尖大佬，可以自行翻翻CSDN和一些书籍给自己一个满意的回答）

## Git介绍

**建议查阅维基百科给出相应解释**：https://en.wikipedia.org/wiki/Git

## Git安装教程

**建议查阅网站**：https://www.runoob.com/git/git-install-setup.html

或者 https://www.liaoxuefeng.com/wiki/896043488029600/896067074338496

在使用教程之前，不妨先看看自己有没有在某个时候不小心已经安装了git了：

在命令行输入$ git, 如果你已经安装过了，就直接跳到工作流程部分吧！

### Windows安装Git

直接利用Git官网的下载链接：https://git-scm.com/downloads

默认选项点到底，完成后在win菜单中的Git文件夹找到Git Bash，则安装完成。

### Linux安装Git

较新版本的Debian和Ubuntu系统可以直接使用命令行 $ sudo apt-get install git 完成安装

较老版本的则使用  $ sudo apt-get install git-core 命令

### Macos安装Git

打开你的App Store，下载（很多人应该已经下载了）Xcode即可，虽然Xcode集成了Git，不过默认没有安装。运行Xcode后，选择菜单“Xcode”->“Preferences”，在弹出窗口中找到“Downloads”，选择“Command Line Tools”，点“Install”即可。

### Git文件配置

- 初次使用Git，需要通过命令行配置个人用户名称和电子邮件地址

  ```bash
  $ git config --global user.name "用户名称"
  $ git config --global user.email test@mails.tsinghua.edu.cn
  ```

## Git工作流程

### 创建仓库



### 基本操作

**git clone**、**git push**、**git add** 、**git commit**、**git checkout**、**git pull**

讲讲这些基本流程就行

### 分支管理 

## Git GUI：让Git工作流程更加清晰

介绍常用的Git GUI

## Git in Vscode

