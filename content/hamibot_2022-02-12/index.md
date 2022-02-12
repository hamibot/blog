+++
title = "更新日志 #220211"
date = 2022-02-12
slug = "changelog 20220211"

[extra]

[taxonomies]
tags = ["HAMI 更新"]
+++

## 新增

- 订阅 API 配额（更多的 API 请求次数） [查看](https://hamibot.com/account/quotas)
- 查询 API 使用情况 [查看](https://hamibot.com/account/quotas)
- 旧版微信登录入口（仅限无密码、无邮箱且有交易记录的用户，登录后请及时设置邮箱和密码） [查看](https://hamibot.com/login/wechat_pay)
- REST API 支持调用私有脚本 [文档](https://docs.hamibot.com/rest/reference#开发脚本)

## 变动

- REST API 取消日配额限制
- REST API 每月免费配额 300

## 修正

- 同时运行脚本时，部分环境信息错误 [@Eplus](https://hamibot.com/Eplus)
