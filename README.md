# gridea-theme-inlineamp

InlineAMP 是一款纯 [AMP](https://amp.dev/) 主题，设计上简约、干净、响应式，适合喜欢极简设计、比较在意页面打开速度的博主使用。

<!-- more -->

下载：https://github.com/jiansing/gridea-theme-inlineamp/releases

预览：https://gridea-theme-inlineamp.netlify.app/

演示站托管在 netlify 并启用了[AMP 服务器端渲染](https://amp.dev/documentation/guides-and-tutorials/optimize-and-measure/server-side-rendering/)，拥有更快的速度。

## 测速报告：
### gtmetrix.com
测速位置：香港   网络：不受限制
首屏仅需 0.6s
<iframe src="https://gtmetrix.com/reports/gridea-theme-inlineamp.netlify.app/E494RVXu/video" width="640" height="548" frameborder="0" scrolling="no" allowfullscreen></iframe>

测速位置：香港   网络：LTE Mobile (15/10 Mbps, 100ms)
首屏仅需 1.1s
<iframe src="https://gtmetrix.com/reports/gridea-theme-inlineamp.netlify.app/J0Xi8LW8/video" width="640" height="548" frameborder="0" scrolling="no" allowfullscreen></iframe>

pagespeed insights 报告：https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fgridea-theme-inlineamp.netlify.app
（手机端分数低是因为延迟加载了视口外的图像，并且我放的几张图像没有压缩过。如果将图片压缩、调整大小分数会更高，但即使用了也不影响首屏的速度）




## 使用指南

插入图片、视频、音频
https://jiansing.github.io/include-images-and-video/

添加评论
https://jiansing.github.io/add-comment-for-gridea-theme-inlineamp/

## v1.3.0-beta.0 updated 2020.4.26

NEW：

### 外观

1. 可以更精细地调整主题配色（注意有些配置项要滚动下拉才能看到）
2. 预置两种配色方案
3. 支持自定义 CSS
4. 支持公共顶部设置图片作为背景

### 评论

1. 支持五种评论系统：Gitalk、Valine、Utterances、Disqus、Facebook

### SEO

1. 支持 SEO Meta
2. 支持 Google JSON-LD 结构化数据：博客文章、面包屑、Logo

### 侧边栏

1. 可以更换不同的搜索引擎

### 其他

1. 增加了主题更新提醒

Gitalk、Valine、Utterances 评论系统均以能够通过 AMP 验证的方式实现，由于不是官方给出的实现方案，可能存在一些常规情况下不会出现的问题，在后面的版本中随时可能被移除。


移植于wordpress的同名主题 InlineAMP 。（[原主题Github](https://github.com/justid/InlineAMP)）

## 继承了原主题的一些特点：
- 纯AMP主题（极致速度体验）
- 移动端/PC端响应式布局（Flex布局）
- Pure CSS design（无图设计）
- 极简&科技风格（简约但不简单）

## 简单但够用：
### 顶部标语
![](https://i.loli.net/2020/03/18/Qa9JNCj2y8x3ebz.png)

可以设置主/副标语，将显示在每个页面的顶端

### 友链
![](https://i.loli.net/2020/03/18/e3M1SzjdKPyfDLT.png)

在侧边栏显示友链

### Disqus评论
![](https://i.loli.net/2020/03/18/5WbgXrvoBfjmtpl.png)

支持Disqus评论

### 按需加载JS
![](https://i.loli.net/2020/03/18/GjLah3yqucfBDop.png)

### Google Analytics
![](https://i.loli.net/2020/03/18/mrSz7qdMAJiPNg3.png)

可以添加Google Analytics

### 语言
用于设置 html lang 属性，默认设置为简体中文(zh-Hans)，一般用默认设置即可


## 待实现的功能

- 标签云页面
- PWA 支持
- 主题自定义
- 代码高亮






