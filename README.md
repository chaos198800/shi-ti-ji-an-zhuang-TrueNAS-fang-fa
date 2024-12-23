# 实体机安装TrueNAS方法

本文详细介绍了如何在实体机上安装TrueNAS SCALE系统。内容包括下载镜像、创建启动盘、设置主板启动项、初始化系统及无启动盘的硬盘直接启动步骤。请确保设备不是NAS专用设备，并在操作前备份重要数据。

## 步骤概览

1. **下载镜像**  
   从TrueNAS官网下载TrueNAS SCALE镜像。

2. **创建启动盘**  
   使用Rufus工具创建一个16GB以上的启动盘，可以是U盘或TF内存卡+读卡器。

3. **设置主板启动项**  
   进入主板BIOS设置，将启动顺序调整为从创建的启动盘启动。

4. **初始化系统**  
   启动TrueNAS安装程序，按照提示进行系统初始化设置。

5. **无启动盘的硬盘直接启动**  
   如果设备没有启动盘，可以直接从已安装TrueNAS的硬盘启动。

## 注意事项

- 确保设备不是NAS专用设备（如微形计算机、淘汰下来的废弃主机或主板）。
- 提前准备一个小一点的硬盘（32GB），防止误将硬盘系统化而无法识别。
- 操作前备份重要数据，以防数据丢失。

通过以上步骤，您可以在实体机上成功安装TrueNAS SCALE系统，并开始使用其强大的存储和管理功能。

## 下载链接

[实体机安装TrueNAS方法](https://pan.quark.cn/s/dc1ee67f6ec9)