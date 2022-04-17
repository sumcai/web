---
title: test
permalink: /xxx/xxx/
categories:
  - 测试
tags:
  - 测试文章
date: 2022-04-15 20:45:52
---

| `layout`     | 布局                 | [`config.default_layout`](https://hexo.io/zh-cn/docs/configuration#文章) |
| ------------ | -------------------- | ------------------------------------------------------------ |
| `title`      | 标题                 | 文章的文件名                                                 |
| `date`       | 建立日期             | 文件建立日期                                                 |
| `updated`    | 更新日期             | 文件更新日期                                                 |
| `comments`   | 开启文章的评论功能   | true                                                         |
| `tags`       | 标签（不适用于分页） |                                                              |
| `categories` | 分类（不适用于分页） |                                                              |



### 1. 前言

{% link 糖果屋教程贴, https://akilar.top/posts/615e2dec/, https://npm.elemecdn.com/akilar-candyassets/image/siteicon/favicon.ico %}

[Hexo](https://link.zhihu.com/?target=https%3A//hexo.io/zh-cn/)是一个快速、简洁且高效的博客框架。Hexo 使用 [Markdown](https://link.zhihu.com/?target=http%3A//daringfireball.net/projects/markdown/)（或其他渲染引擎）解析文章，在几秒内，即可利用靓丽的主题生成静态网页。即把用户的markdown文件，按照指定的主题解析成静态网页。

1. 模版文件夹。新建文章时，Hexo 会根据 scaffold 中的模板文件来建立新的文件。

2. **Hexo的模板是指在新建的markdown文件中默认填充的内容**。

   - 使用绝对路径引用资源，在 Web 世界中就是资源的 URL

   - 使用相对路径引用资源
   - 使用文本编辑器打开站点根目录

3. 例如，如果修改scaffold/post.md中的Front-matter内容

4. 那么每次新建一篇文章时都会包含这个修改。也就是说，通过hexo命令每新建一个文章，都会包含指定模板文件中的内容。

写个博客，有时候会想添加个图片或者其他形式的资源等等。有以下两种方式进行解决：

- 使用绝对路径引用资源，在 Web 世界中就是资源的 URL

- 使用相对路径引用资源
- 使用文本编辑器打开站点根目录

对于使用相对路径引用资源的，我们可以使用 Hexo 提供的**资源文件夹**功能。

使用文本编辑器打开站点根目录下的 `_ config.yml` 文件，将 `post_asset_folder` 值设置为 