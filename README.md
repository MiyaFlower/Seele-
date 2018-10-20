# Electron 开源库 + Angular 6 框架 + NSIS 制作安装程序工具

# Electron 是一个使用 JavaScript, HTML 和 CSS 等 Web 技术创建原生程序的框架。

# Angular 是一个开发平台。更轻松的构建 Web 应用。集声明式模板、依赖注入、端到端工具和一些最佳实践于一身， 为开发者提升构建 Web、手机或桌面应用的能力。

# NSIS（Nullsoft Scriptable Install System）是一个开源的安装程序制作工具。它提供了安装、卸载、系统设置、文件解压缩等功能。

# 构建应用程序流程

# 官网地址

# Electron

# 官网地址：https://electronjs.org/
# Github地址：https://github.com/electron/electron-quick-start

# Angular

# 官网地址：https://www.angular.cn/

# NSIS

# 《钱包调研》NSIS -> NSIS压缩包

# 环境搭建

# Node
# Git
# Visual Studio Code
# NSIS VNISEdit 编译环境

# 应用程序构建命令

# Electron

# 克隆示例项目的仓库
# $ git clone https://github.com/electron/electron-quick-start

# 进入这个仓库
# $ cd electron-quick-start

# 安装依赖并运行
# $ npm install && npm start

# Electron应用程序启动界面：
 

# 找到Electron应用程序存放路径：
# C:\Users\Administrator\AppData\Roaming\npm\node_modules\electron\dist    electron.exe
 
# Angular （暂时可忽略）

# 全局安装 Angular CLI
# npm install -g @angular/cli

# 创建新项目
# ng new my-app

# 启动开发服务器
# cd my-app
# ng serve --open

# NSIS

# 下载NSIS软件
# 安装NSIS中文版下载地址：https://pan.baidu.com/s/1mitSQU0

# 安装asar

# 参考官方文档https://www.w3cschool.cn/electronmanual/cexo1qkn.html
# npm install -g asar

# 生成asar包

# 在electron目录F：/electron-quick-start下执行下面命令，生成asar包
# asar pack ./index.html app.asar
# 得到app.asar包
 
# app.asar 存放位置

# 将app.asar放到文章开始图片得到目录下的resources文件夹下
 
# 打开NSIS

# 选择可视化脚本编辑器

# 选择使用脚本向导创建新的脚本文件，确定

# 下一步
 
# 设置安装程序

# 设置安装程序图标(图标必须是ico格式)，名称，语言（SimpChinese），界面，然后下一步

# 默认,直接下一步
 
# 授权文件

# 授权文件有就填，没有就填空白,然后下一步
 
# 添加应用程序文件，默认两个文件选中，删除
 
# 点击添加文件

# 添加HelloWorld.exe文件，确定
 
# 点击AddDirTree
 
# 修改开始菜单名称

# 可修改开始菜单名称，然后下一步
 
# 设置安装成功后启动的程序

# 设置安装成功后启动的程序，默认就是我们打包后的启动程序，下一步
 
# 设置卸载界面

# 设置一些卸载时界面的提示信息，然后下一步
 
# 保存脚本

# 保存脚本，完成，保存到桌面
 
# 打开脚本文件，编译及运行
 
# 安装
  
# 构建成功




