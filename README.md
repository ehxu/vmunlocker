适用于VMware Workstation的macOS Unlocker V3.0
-----------------------------------------

本项目魔改自大佬[Paolo](https://github.com/paolo-projects/unlocker/)的一个项目，因国内下载`darwin.iso`和`darwinPre15.iso`下载速度不佳，于是在此项目中集成，VMTools镜像目录在`/tools/`下。

## 1.简介

Unlocker 3专为VMware Workstation 11-16和Player 7-15设计（经测试VM16时依旧可以使用）

第3版已针对以下方面进行了测试：

* Windows和Linux上的工作站11/12/14/15/16
* Windows和Linux上的Workstation Player 7/12/14/15

请注意，并非所有产品都能通过安装工具菜单项识别darwin.iso。
您将必须手动安装darwin.iso，例如在Workstation 11和Player 7上。

在所有情况下，请确保VMware未运行，并且任何后台guest虚拟机具有
已关闭。

该代码是用Python编写的。

2.使用须知
----------------

该代码需要Python 2.7才能运行。大多数Linux发行版附带兼容的
Python解释器，无需任何其他软件即可正常工作。

Windows Unlocker具有使用PyInstaller的Python脚本的打包版本， 
因此不需要安装Python。

## 3.使用方法

下载本项目源码，直接右键以管理员身份运行：`win-install.cmd`  即可

VMTools的`darwin.iso`和`darwinPre15.iso`ISO存放路径：`C:\Program Files (x86)\VMware\VMware Workstation\`

4.谢谢
---------

感谢所有参与本项目的原作者！
