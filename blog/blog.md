---
slug: blog
title: blog
author: runhua
author_title: 前端菜鸟
author_url: 'https://fanyi.youdao.com/'
author_image_url: 'https://gitee.com/yaorunhua/runbed/raw/master/img/LX_work/anatomy-of-an-html-element.png'
tags: [blog, docusaurus]
---
代码块

```bash
git init #在本地文件目录(工作区)下执行该命令,创建本地版本库
```
<!--truncate-->
## 1.HTML

超文本标记语言（Hypertext Markup Language)

### 1.概念引入

- [**HTML**](https://developer.mozilla.org/zh-CN/docs/Glossary/HTML)

  [HTML](https://developer.mozilla.org/zh-CN/docs/Glossary/HTML) (HyperText Markup Language) 不是一门编程语言，而是一种用来告知浏览器如何组织页面的**标记语言**

  HTML（超文本标记语言） 是一种描述语言，用来**定义网页结构**

- **HTML文档**

  HTML 文档是包含多个 [HTML 元素](https://developer.mozilla.org/zh-CN/docs/Glossary/Element) 的**文本文档**。每个元素都用一对开始和结束 [标签](https://developer.mozilla.org/zh-CN/docs/Glossary/Tag) 包裹。每个标签以尖括号（`< >`）开始和结束。也有一部分标签中不需要包含文本，这些标签称为空标签(自结束标签)，如 `<img>`

- [HTML 元素](https://developer.mozilla.org/zh-CN/docs/Glossary/Element) 

  HTML元素一般构造如下👇

  

  ![](https://gitee.com/yaorunhua/runbed/raw/master/img/LX_work/anatomy-of-an-html-element.png)

  

  在 HTML 中, 标签用来创建元素

  标签举例: 

  ```html
  - <em>  斜体强调标签 
  - <strong> 加粗强调标签
  - <p> 段落标签
  ```

### 2.块级元素和内联元素,空元素

- 