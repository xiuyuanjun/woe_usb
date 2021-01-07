# uefi-ntfs

#### 介绍
linux上制作Windows安装U盘所需文件

执行文件来自于：

https://github.com/pbatard/uefi-ntfs
https://github.com/WoeUSB/WoeUSB

#### 软件架构
软件架构说明

#### 使用说明

1.  格式化掉U盘里所有分区
2.  下载woeusb文件即可,uefi-ntfs会在执行期间自动下载，已修改脚本中下载路径指向为当前项目里的uefi-ntfs.img
2.  执行以下命令
    ```
    sudo ./woeusb --tgt-fs NTFS  --device xxx.iso /dev/sdc
    ```
3.  等待完成