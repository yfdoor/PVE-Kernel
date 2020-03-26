# PVE-Kernel

## 简介：
- 该项目用来在线编译 PVE 核心以修正 IOMMU 不能分组的问题。

## 功能：
- 本方案通拉取官方镜像 https://git.proxmox.com 中的 **PVE-Kernel**。
- 然后复制 patches 下的文件替换源码中的原文件。
- 最后重新编译打包 kernel 文件，更新核心的方法来解决 IOMMU 不能分组的问题。

## 下载：
- 下载 **Kernel-Package** 分支或 **Artifacts** 下的：**PVE_Kernel_yfdoor.zip** 压缩包然后安装新的核心文件即可。
- 码云镜像：https://gitee.com/yfdoor/PVE-Kernel-G

## 警告：
- 更新核心有风险，请谨慎操作。
