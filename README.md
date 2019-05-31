# ralink_uboot

注意，本项目只能在32位linux环境下进行

Ralink官方uboot源码，提取自MediaTek_ApSoC_SDK_4320_20150414.tar

在使用前需要在Linux中更新 gcc 版本 ，

gcc 版本不能高于 3.5.2 ，否则uboot会编译失败

可在releases中找3.4.2版本的gcc, buildroot-gcc342.tar.bz2

1.下载
```Barsh
  git clone git clone https://github.com/maxlicheng/ralink_uboot.git
```


2.更新Linux gcc
```Barsh
  #在releases中找3.4.2版本的gcc, buildroot-gcc342.tar.bz2
  #可直接用wget命令下载
  wget https://github.com/maxlicheng/ralink_uboot/releases/download/V1.0/buildroot-gcc342.tar.bz2
```
