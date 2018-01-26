# Jupyter Notebook使用笔记
## Jupyter Notebook介绍

用Python编代码常用的两个工具：**Pycharm**和**Jupyter Notebook**。
**Pycharm**是Python的集成开发环境这没错，但我们通常也认为**Jupyter Notebook**也是一个**Python IDE**。其实它是一款交互式的编程与展示web的工具而已，并不是一个**Python IDE**(很简单判断，它没有自动补全提示等功能)。

## Jupyter Notebook安装
Jpuyter有多种安装方式，常用的就是直接下载安装Anaconda，里面有自带的Jupyter notebook。第二种就是使用pip来安装，命令pip install jupyter。
启动方式可以直接在Anaconda找到Jupyter notebook启动
![image](https://github.com/MingQuanXu/Notes-of-using-Jupyter-Notebook-/Photo.JPG)

## Jupyter Notebook的一些概念和快速开发技巧（notebook里面每一个叫做cell）

* **两种模式**
Command mode 和 Edit mode。 在一个cell中，按下Enter进入Edit mode,按下Exc进入Command mode

* **运行当前cell,并移到下一个cell**
在一个cell中（Command mode）,按下Shife + Enter

* **创建cell**
在一个cell中（Command mode）,按下a,在这个cell之前创建一个新的cell, 按下b,在这个cell之后创建一个新的cell

* **删除cell**
在一个cell中（Command mode），按下两次d

* **保存notebook**
在一个cell中（Command mode）,按下s

* **启动命令面板**
在一个cell中（Command mode）,按下Ctrl + Shift + P