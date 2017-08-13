# ZJUNIX ToolBox

## 简介

![ZJUNIX ToolBox](https://img.shields.io/badge/ZJUNIX-ToolBox-blue.svg)

此工程为 ZJUNIX 专用的工具包，其编译的工具可以在 ZJUNIX 中使用外部命令加载工具进行加载并运行

## 使用简介

### 准备工作

1. 请在 config/tools.conf 文件夹下修改交叉编译工具与 make 工具的路径，具体修改细节请参考 ZJUNIX 工程的 Readme

### 编译

1. 参考 ZJUNIX 编译方式与当前已有代码的 Makefile 进行编译

### 安装与执行

1. 将编译生成的 .bin 文件复制到 SD 卡中
1. 在 ZJUNIX 启动之后，使用 exec 命令等方式加载这个 .bin 文件来执行

## 协议

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

此工程遵循 BSD3 协议