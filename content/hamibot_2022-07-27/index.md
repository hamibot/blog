+++
title = "Hamibot 更新日志"
date = 2022-07-27
slug = "changelog220727"

[extra]

[taxonomies]
tags = ["HAMI 更新"]
+++

# 20220727

## 新增

- 一键导入 GitHub 脚本
- 通知定时任务失败原因
- 生成优惠码支持设定使用的订阅周期
- 保护源码功能 [前往查看](https://hamibot.com/dashboard/scripts/console)

[![导入脚本到 Hamibot](https://hamibot.com/badge_import.png)](https://hamibot.com/dashboard/scripts/import?url=https%3A%2F%2Fgithub.com%2Fhamibot%2Fscript)

## 修正

- 脚本订阅升级
- 私有脚本分享，每次发布时会重置为否

# 20220628

## 新增

- 脚本推荐奖励
- 脚本支持升级订阅
- 客户端 Hamibot 1.4.3
- 优惠码支持限定付费周期
- 优惠码支持前缀

## 变动

- 同时有效的优惠码数量调整为 30

# 20220613

## 新增

- 支持分享私有脚本
- 重新生成脚本邀请码

## 变动

- 支持年付订阅

# 20220530

## 新增

- 项目主可私聊开发者
- 脚本用户可直接查看私有脚本
- 开发者可设定脚本的运行机器人数量
- 开发者可创建优惠码
- REST API 支持删除脚本 [前往查看](https://docs.hamibot.com/rest/reference)

# 20220510

## 新增

- 脚本搜索使用新引擎
- 脚本搜索可载入更多结果
- 项目支持私聊需求方
- REST API 示例代码 [前往查看](https://docs.hamibot.com/rest/reference)
- 付费议题（用户创建的脚本议题，需支付费用）

## 变动

- 取消 GitHub 登录时更新资料

## 修正

- 修正 REST API 消息推送报错机器人版本过低

# 20220505

## 新增

- 项目功能，可付费寻找开发者，定制脚本 [前往查看](https://hamibot.com/projects)
- 议题标记是否有新回复
- 支持切换站点（国际站全功能，部分地区访问较慢；国内站速度快，功能较少）
- 开发者保证金计划，加入可获得额外权限 [前往查看](https://hamibot.com/account/developer)

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
