+++
title = "Hamibot 更新日志"
date = 2022-08-30
slug = "changelog220830"

[extra]

[taxonomies]
tags = ["HAMI 更新"]
+++

# 20220830

## 新增

- 复制脚本、机器人 ID，方便用于 REST API 和 VSCode 插件
- ✨ 发布 VSCode 插件，方便本地远程调试脚本 [安装地址](https://marketplace.visualstudio.com/items?itemName=hamibot.vscode-hamibot)
- ✨ 消息推送 API [文档](https://docs.hamibot.com/rest/reference#%E6%B6%88%E6%81%AF%E6%8E%A8%E9%80%81-1)

## 修正

- 项目关闭异常

## 其他

✨ VSCode 插件 ✨

千呼万唤始出来，终于支持本地远程调试脚本了，欢迎使用、给星、提 PR

源码地址：https://github.com/hamibot/vscode-hamibot

✨ 消息推送 ✨

新消息推送提高了易用性，支持 GET、POST 方式，适应更广泛的应用场景，可用于监控报警。
