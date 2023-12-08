---
title: "hugo--问题记录"
date: 2023-12-08T16:42:21+08:00
draft: false

author: ["Xiaoli"]

categories: 

- exp

tags: 

- hugo

showToc: true # 显示目录
TocOpen: true # 自动展开目录
---

# 问题

## 部署到github时，action失败

- 失败提示 `"The process '/usr/bin/git' failed with exit code 128"`

- 可能原因： 
    + token过期。需要在`主页->settings->Developer Settings->Personal access tokens`重新生成。并且在`项目->settings->Secrets and Variables->actions` 中配置。

