# PVE-Kernel Compile Program

## 简介：
- 该项目用来在线编译 PVE 核心以修正 IOMMU 不能分组的问题。

## 功能：
- 本方案通拉取官方镜像 https://git.proxmox.com/git/pve-kernel.git
- 然后复制 patches 下的文件替换源码中的原文件。
- 最后重新编译打包 kernel 文件，更新核心的方法来解决 IOMMU 不能分组的问题。

## 用法：
- 将 PVE-Kernel-CI.yml 文件放到你的项目 .github/workflows/ 目录下，然后点击 “star” 来触发。

## 下载：
- 下载 Kernel-Package 分支下的：**[PVE_Kernel_yfdoor.zip](https://github.com/yfdoor/PVE-Kernel/blob/master/PVE_Kernel_yfdoor.zip)** 或 **Artifacts** 下的压缩包即可。

## 警告：
- 更新核心有风险，请谨慎操作。
