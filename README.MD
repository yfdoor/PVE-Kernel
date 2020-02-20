# PVE-Kernel Compile Program

## 简介：
该项目用来在线编译 PVE 核心以修正 IOMMU 不能分组的问题。

## 方案：
- 本方案通拉取官方镜像 https://git.proxmox.com/git/pve-kernel.git，
- 然后修改 patches 下的 ACS 文件。
- 最后重新编译打包 kernel 文件，更新核心的方法来解决 IOMMU 不能分组的问题。

## 用法：
将 PVE-Kernel-CI.yml 文件放到你的项目 .github/workflows/ 目录下，然后点击 “star” 来触发。

## 警告：
更新核心有风险，请谨慎操作。
