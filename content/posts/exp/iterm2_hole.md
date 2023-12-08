---
title: "iterm2--问题记录"
date: 2023-02-02T17:45:42+08:00
draft: false

categories:
- exp

tags:
- iterm2
---

# 问题

## rz上传文件成功，但是在当前目录无法找到所上传文件

-  rz上传文件至服务器时，默认会上传到当前目录。

- 若显示**上传成功**，但无法找到该文件，与连接服务器的方式有关。

- 检查是否连接时使用了expect脚本，需要修改为: ssh xxx.xxx.xxx 的连接方式。

  
