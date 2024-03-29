---
title: Markdown基本使用
keywords: Markdown基本使用
desc: teedoc 生成静态博客页面, Markdown基本使用
author: wuboy19
date: 2023-05-29
tags: markdown, blog
---




这是一段测试简介，会显示在列表中，使用`<!-- more -->`来分隔正文

<!-- more -->


##Markdown的简介介绍

Markdown 是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档。  
Markdown 语言在 2004 由约翰·格鲁伯（英语：John Gruber）创建。  
Markdown 编写的文档可以导出 HTML 、Word、图像、PDF、Epub 等多种格式的文档。  
Markdown 编写的文档后缀为 .md, .markdown。  

##Markdown的语法介绍
###标题
```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```
###换行

方法一：直接在一句话后面敲两个空格   
方法二：两句话之间加一个TAB键    
方法三：如果你在编辑的时候，想让一行文字分成几段在显示的时候换行，就在中间加```<br/>```

###字体
```
*斜体文本*
_斜体文本_
**粗体文本**
__粗体文本__
***粗斜体文本***
___粗斜体文本___
```
具体效果如下：     
*斜体文本*  
_斜体文本_  
**粗体文本**    
__粗体文本__    
***粗斜体文本***     
___粗斜体文本___ 

###分割线
```
***
* * *
*****
- - -
----------
```

###删除线
```
~~删除线~~
<u>下划线</u>
```
具体效果如下：
~~删除线~~
<u>下划线</u>

###分点条列
```
* 第一行
* 第二行

- 第一行
- 第二行

+ 第一行
+ 第二行
```
* 第一行
* 第二行
- 第一行
- 第二行
+ 第一行
+ 第二行

###区块
markdown区块是在段落开头使用 “>”，依然是紧跟空格
```
> markdown
> 基础
> 区块引用
```
> www  
> wwwwwww

1、区块嵌套
```
> markdown
>> 基础
>>> 区块引用
```
> www  
>> wwwwwww
>>> wwwwwwww

2、区块中使用列表
```
> 区块中使用列表
> 1. 第一项
> 2. 第二项
>> + 第一项
>> + 第二项
>> + 第三项
```

效果如下：
> 区块中使用列表
> 1. 第一项
> 2. 第二项
>> + 第一项
>> + 第二项
>> + 第三项

###插入代码
* 插入一行代码  
```
`char a[10]={0};`
```
具体效果如下：
`char a[10]={0};`
+ 插入代码块
```
```这样操作
char a[10]={0};
char b[10]={0};
```这样操作
```
具体效果如下：
```
char a[10]={0};
char b[10]={0};
```
###插入链接
```
[链接名称](链接地址)
或者
<链接地址>
[本作者链接](https://wuboy19.github.io/)  
[本作者链接]<https://wuboy19.github.io/>
```
例如：  
[本作者链接](https://wuboy19.github.io/)  
[本作者链接]<https://wuboy19.github.io/>

###插入图片
```
![图片描述，可写可不写，但是中括号要有](图片地址，本地链接或者URL地址。)
![图片](https://img-blog.csdnimg.cn/img_convert/c0bf36997569bd083fa76e0632a14ef4.png)  
![图片](../../../wuboy19.github.io/static/image/logo.png)
```
具体效果如下：
![图片](https://img-blog.csdnimg.cn/img_convert/c0bf36997569bd083fa76e0632a14ef4.png)  
![图片](../../../wuboy19.github.io/static/image/logo.png)

###插入表格
```
|  表头   | 表头  | 表头 | 表头 |
| :---  | ---:  | :--: | ---- |
| 单元格  | 单元格 |单元格|单元格|
| 单元格  | 单元格 |单元格|单元格|
```
具体效果如下：

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

###12、支持HTML元素
不在 Markdown 涵盖范围之内的标签，都可以直接在文档里面用 HTML 撰写
使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑


####pycharm不支持[TOC]目录生成；
