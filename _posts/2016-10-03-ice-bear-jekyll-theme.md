---
layout: post
title:  "Markdown 常用语法"
date:   2021-09-25 15:52:30 +0800
categories: [Tech]
excerpt: 这是一个markdown 常用语法描述，用于自己写博客查看.
tags:
  - jekylI
  - markdown
---
## 文字样式的编辑

> \**演示粗体\**
> \*演示斜体\*
效果

> **演示粗体**
> *演示斜体*

## 对段落的编辑
\+ 演示列表
    \+ 列表还可以有层级
    
\> 这是引用文字的效果

效果
+ 演示列表
    + 列表还可以有层级
    
> 这是引用文字的效果

## 插入文章其他元素
\[少数派](https://sspai.com)

\![](https://cdn.sspai.com/attachment/thumbnail/2016/11/04/264631b984633898c415a818b181e5205653e_mw_640.jpg)

效果
[少数派](https://sspai.com)

![](https://cdn.sspai.com/attachment/thumbnail/2016/11/04/264631b984633898c415a818b181e5205653e_mw_640.jpg)

代码块增强
    \```python
    def 点赞机():
        if 文章不错：
            return 点赞
        else:
            return 差评
    \```
效果
    ```python
    def 点赞机():
        if 文章不错：
            return 点赞
        else:
            return 差评
    ```

要插入文章元素方面，它支持在 Markdown 里写表格，如果你这么写：
\| First Header  | Second Header |
\| ------------- | ------------- |
\| Content Cell  | Content Cell  |
\| Content Cell  | Content Cell  |
效果

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

# Installation
---

* Fork the repository. <iframe src="https://ghbtns.com/github-btn.html?user=songkong&repo=Blog&type=fork&count=true" frameborder="0" scrolling="0" width="170px" height="20px"></iframe>
* Edit `_config.yml` file.
* Add your own `projects` in `_includes/projects.html`.
* Change `domain name` in `CNAME`.
* Replace `favicon.ico` with your website icon.
* Change `avatar.jpg` and `cartoon-avatar.jpg` in `assets/images`.
* Edit `LICENSE.md` and `README.md`.

> I use two categories for posts in my blog, `Tech` and `Life`. If you want to add other categories, remember to modify `_includes/post-list-pagination`, `_layouts/post-list.html` and `assets/js/script.js` to add `Tabs` and `Paginations` for every category posts. 

# Style test
---

_italic_. **bold**. ***italic and bold***. ~~delete line~~. [link](http://kongsong.me).

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

>### Heading 3 in Blockquotes
>Normal Blockquotes text.
>
>* Unordered List in Blockquotes.
>
>1. Ordered List in Blockquotes.

* Unordered List.
	* Unordered List.

1. Ordered List
	1. Ordered List
	2. Ordered List
2. Ordered List
	

{% highlight ruby %}
// Ruby codes

require 'parallel'

Parallel.map(lots_of_data) do |chunk|
  heavy_computation(chunk)
end
{% endhighlight %}

table | table | table | table | table
----|------|---- | ---- | ---- 
This is table | This is table | This is table | This is table | This is table
This is table | This is table | This is table | This is table | This is table

