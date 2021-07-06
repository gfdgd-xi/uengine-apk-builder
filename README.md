# uengine APK 打包器 1.0.0

#### 介绍

使用 Python3 的 tkinter 构建

（测试平台：UOS 家庭版，deepin 20.2.2）

（自己美术功底太差，图标直接用 anbox 的了）

#### 软件架构
全部，不过打出来的包就……

#### 更新内容

1.0.0更新内容：
1、无


#### 源码安装教程

1.  安装所需依赖

```
sudo apt install python3 python3-tk git python3-pip aapt
pip3 install pillow
pip3 install ttkthemes
pip3 install pillow -U
pip3 install ttkthemes -U
```

2.  下载本程序

```
git clone https://gitee.com/gfdgd-xi/uengine-apk-builder.git
```

3.  运行本程序

```
sudo cp uengine-apk-builder /opt/apps -rv
chmod 777 /opt/apps/uengine-apk-builder/main.py
sudo cp /opt/apps/uengine-apk-builder/main.py /usr/bin/uengine-apk-builer
./main.py
```

4.  卸载本程序
```
sudo rm /usr/bin/uengine-apk-builder -v
sudo rm /opt/apps/uengine-apk-builder/ -rfv
pip3 uninstall pillow
pip3 uninstall ttkthemes
```

#### 使用说明

提示：
无

如果想要连接其他手机，请使用 1.2.0 以前的版本，可以使用 adb 连接。


#### 特技

……
