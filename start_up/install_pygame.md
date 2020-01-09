# install pygame 安装pygame


### why pygame 为什么选择pygame
pygame 是一个成熟的、丰富的python库，非常适用于创建2D的小游戏，尽管很难利用pygame进行商用生产，但是pygame是初学者非常值得尝试的，这也将会抛掉许多底层技术的束缚，让我们专注于高级语言层面的逻辑开发。


### how to instal 如何安装？

* 下载pygame有两个渠道：
1. [下载地址1](https://bitbucket.org/pygame/pygame/downloads/)
2. [下载地址2](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pygame)


**要注意的是**：
1. 文件名"cp"后的36代表的是python版本号3.6，cp27代表python2.7，最新版的python版本为3.8，
所以**如果下载了python3.8，请选择下载地址2**
2. Windows用户选择带win的版本号，32位处理器选择win32，64位处理器选择win——amd64.
3. 两个网站服务器均在美国，所以请科学上网后再下载文件
4. 文件夹内上传了python3.8 Windows64位处理器的pygame文件，需要的话也可以直接下载。


* **安装**：

1. 首先确保你的电脑安装了与pygame对应版本的python，且安装python时选择安装了pip。
2. 将下载好的.whl文件放入游戏开发所使用的文件夹
3. win + R快捷键输入cmd打开命令行终端
4. 输入 `Python -m pip install pygame-1.9.6-cp38-cp38-win_amd64.whl`
5. 界面显示installed证明安装完成
6. 使用python shell尝试import pygame，如果报错：
* 查看python版本与pygame是否相符，非常注意编辑器左（右）下角显示所使用的python版本号（有可能使用了anaconda安装的python3.7与重新下载的python3.8共存，要点击编辑器/IDE的python版本号直接更改）
* 如果python shell未报错而编机器报错：
打开命令行终端，进入游戏开发使用的文件夹，输入`pip install pygame`
得到一个地址，截取到python38，查找到该目录，把目录下的site-packages复制到pycharm项目路径下的site-packages即可。

**接下来就可以愉快的开发啦:D**