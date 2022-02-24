# Hamibot Blog

[Hamibot 博客](https://blog.hamibot.com/)

## 投稿

🙏 期待大家的投稿！

1. Fork 本项目

2. Clone 到本地

`git clone https://github.com/<你的用户名>/blog.git`

3. 新建文章文件夹

在 `content` 下新建一个文件夹，命名格式：

`GitHub 用户名 + 下划线 + 日期`

例如：`hamibot_2022-02-24`

4. 新建 `index.md`

在文件夹下创建 `index.md` 文件，添加文章信息，格式：

```yml
+++
title = "文章标题"
date = 日期
slug = "文章链接" # 可选
[extra]
author = "作者名称"
cover = "封面图片" # 可选
[taxonomies]
tags = ["标签","标签2"]
+++
```

例如：

```yml
+++
title = "脚本如何收集错误报告"
date = 2022-02-24
slug = "脚本如何收集错误报告"
[extra]
author = "hamibot"
cover= "cover.png"
[taxonomies]
tags = ["HAMI 进阶"]
+++
# 文章内容
```

5. 创作你的文章

Markdown 格式编写文章内容，所有图片放在文件夹内。

推荐使用 VSCode 配合 [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) 进行编写。

最终文件夹结构：

```
|-- hamibot_2022-02-24
|   |-- index.md
|   |-- cover.png
|   |-- 图片1.jpg
|   |-- 图片2.jpg
|   |-- ...
```

6. Commit 提交

```
git add .
git commit -m "feat: 文章标题"
git push
```

7. 创建 Pull request

8. 等待合并

### 标签

标签一般使用 1-2 个，第一个标签请从下列进行选择：

- `HAMI 与我`
- `HAMI 进阶`
- `技术杂谈`
- `工具妙用`

