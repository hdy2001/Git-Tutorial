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

（关于Git和GitHub的介绍，如果你想浅显的了解，不妨去看看廖雪峰老师的网站。在本教程之中遇到的任何不理解或者陌生的名词和说法，**请先试试百度和谷歌知不知道**）

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

​		在讲解之前，我们希望你了解两个问题：

首先注意，版本控制系统只跟踪文本文件，无法真正跟随图片和视频这些二进制文件的改动，所以我们只讲解文本文件的操作方法。（建议所以的文本编码方式全部采用UTF-8编码，比较普适）

其次注意，本教程默认你的工作环境是Windows，而我们非常不建议你使用Windows记事本来编写txt文件，由于内部编码规则的改变，记事本将会带来各种编译上的错误（微软确实喜欢整这种花活），所以，试试VSCode吧。

### 创建仓库

​		所谓仓库（版本库：repository），其实就是一个独立于你在电脑视窗所看到的文件夹的一个“隐藏文件夹”。这个隐藏的版本库被Git管理，它里面所有文件都被Git跟踪，所以十分方便每个人看到做了什么修改，并且随时还原版本。那么现在，我们就来说说如何在本地创建一个版本库：

首先，在你想要创建版本库的目录下进入bash,输入如下命令行：（路径请不要出现中文!!!)

```bash
$ mkdir learngit
$ cd learngit
$ pwd
/Users/Git Files/learngit
```

/Users/Git Files/learngit也就是当前目录的位置，我们成功创建了一个新目录，接下来就是让Git接管这个目录（或者你可以理解为接管这个文件夹）

输入git init:

```bash
$ git init
Initialized empty Git repository in /Users/Git Files/learngit/.git/
```

此时，当前目录出现了一个被默认隐藏的文件夹（防止你手欠把它删了）叫做.git，这个目录下就是git所管理的repository，一般情况下对我们来说是不可见的，但我们的确创建成功了。

### 基本操作

**git clone**、**git push**、**git add** 、**git commit**、**git checkout**、**git pull**

讲讲这些基本流程就行

###### 接下来我们将文件添加到版本库中保存：

在learngit目录新建一个叫做readme.md（当然你可以选择txt文件或是各种你喜欢的文件类型）的文件，然后使用VSCode写入：

```
Git is a version control system.
Git is free software.
```



### 分支管理 

## Git GUI：让Git工作流程更加清晰

介绍常用的Git GUI

## Git in Vscode

