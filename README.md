# Tengine_For_Arch

#### 介绍
此仓库主要是为了修复在AUR内的tengine无法安装的问题<br>
原因已经找到，主要是文件校验值的问题，已经解决！<br>
为广大的用户提供方便

#### 软件架构
软件架构说明


#### 安装教程

首先克隆这个仓库

```
git clone https://gitee.com/ForMat1_admin/Tengine_For_Arch.git
```

之后进入目录

```
cd Tengine_For_Arch
```
最后执行以下命令安装

```
makepkg -si
```
<hr>
或者在releases内下载安装包后执行以下命令安装

```
pacman -U tengine-2.3.2-1-x86_64.pkg.tar.xz

```
如果提示缺少依赖，请执行这个命令

```
pacman -S geoip geoip-database
```
然后在执行安装包安装命令即可！


#### 使用说明

具体使用方法详见Tengine Wiki或者Nginx Wiki！
### 联系我
QQ：2934301923<br>
Email：hlyAndroid@163.com

