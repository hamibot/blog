+++
title = "Hamibot 更新日志"
date = 2022-04-08
slug = "changelog"

[extra]

[taxonomies]
tags = ["HAMI 更新"]
+++

# 20220408

## 新增

- [课程](https://hamibot.com/courses)，付费学习
- 可选只查看未读通知
- 支持删除邮箱（可用于修改邮箱）
- 工作支持自定义周期限制
- Markdown 支持任务列表
- Markdown 支持折叠
- Markdown 支持语法高亮
- Markdown 支持视频和音频
- Markdown 支持文字标记
- Markdown 支持表情

#### [Markdown 用法参考](https://hamibot.com/markdown)

## 移除

- Markdown 支持 html @Lz1y

# 20220301

## 新增

- 配额支持调整数量
- 评分显示星星分布

## 变动

- 订阅月单位按 31 天计算（对所有 2 月份脚本订阅，增加 2 天有效期） @玉面小白龙阿奴

# 20220223

## 新增

- 任务支持编辑
- 脚本评分，欢迎对脚本评分（评分非实时刷新）
- 脚本支持上传图标
- 用户支持上传头像
- 工作支持评论

# 20220211

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
