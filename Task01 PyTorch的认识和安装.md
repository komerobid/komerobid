什么是PyTorch
PyTorch是由Facebook人工智能研究小组开发的一种基于Lua编写的Torch库的Python实现的深度学习库，目前被广泛应用于学术界和工业界，
而随着Caffe2项目并入Pytorch， Pytorch开始影响到TensorFlow在深度学习应用框架领域的地位。总的来说，PyTorch是当前难得的简洁优雅且高效快速的框架。
不仅能够实现强大的GPU加速，同时还支持动态神经网络。

一、ANACONDA的安装
1、官网上下载ANACODA

2、配置ANACODA的环境变量(D:\Application\ANACONDA\Scripts和D:\Application\ANACONDA，对应的应用下载路径)

3、1）文件管理器文件路径地址栏敲：%APPDATA% 回车，快速进入 C:\Users\电脑用户\AppData\Roaming 文件夹中

   2）新建 pip 文件夹并在文件夹中新建 pip.ini 配置文件
[global]
index-url = http://pypi.douban.com/simple
[install]
use-mirrors =true
mirrors =http://pypi.douban.com/simple/
trusted-host =pypi.douban.com

4、在**C:\Users\电脑用户\找到 .condarc**这个文件,打开后将文件里原始内容删除，将下面的内容复制进去，并且保存
channels:
  - defaults
show_channel_urls: true
default_channels:
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/r
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/msys2
custom_channels:
  conda-forge: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  msys2: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  bioconda: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  menpo: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  pytorch: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  simpleitk: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud

5、torch包的安装
  第一种，打开Pycharm下方的Terminal，输入conda activate test，激活环境并切换到环境下面安装
  第二种，win+R打开命令提示符输入cmd，输入cd D:\Application (pycharm的安装位置),输入pip install torch
  
  
