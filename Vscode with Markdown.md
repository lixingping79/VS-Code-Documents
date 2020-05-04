# 概述
最近为了给业余学习打造一个all in one的编辑器，开始尝试使用VS Code来替代使用了很多年的Source Insight. 
本文用来记述集成**Markdown**相关的插件，配置以及语法。 

## 资料引用
[高鸿祥 Markdown基本语法](https://www.jianshu.com/p/191d1e21f7ed/)

# 插件安装和配置
## Markdown All in One
Markdown All in One 提供了所有需要的功能
```
Markdown: Create Table of Contents  
Markdown: Update Table of Contents
Markdown: Toggle code span
Markdown: Toggle code block
Markdown: Print current document to HTML
Markdown: Toggle math environment
Markdown: Toggle list
```



## Markdown TOC
## Markdown Math
## Markdown PDF
## Markdown Preview Ehanced
## Instant Markdown
## Markdown Theme Kit
# 基本语法
## 标题

在想要设置为标题的文字前面加#来表示
一个#是一级标题，二个#是二级标题，以此类推。支持六级标题。

注：标准语法一般在#后跟个空格再写文字，貌似简书不加空格也行。

## 字体
### 加粗
**加粗**
### 斜体
*斜体*
### 斜体加粗
***斜体加粗***
### 删除线
~~加删除线的文字~~
## 引用
> 这是引用的内容
>> 这是二级引用的内容
## 分割线
---
## 图片
需要使用图床  GITHUB是个不错的选择

## 超链接
[超链接名称](超链接地址)
[百度](http://baidu.com)

##列表
### 无序列表
`无序列表使用-+*都可以， 主要标识符后面要留有一个空格`

- 这是一个无序列表
+ 这是一个无序列表
* 这是一个无序列表


### 有序列表
`有序列表使用数字+.`

1. 这是一个有序列表
2. 这是一个有序列表的第二项

### 列表嵌套
`上一级和下一级之间加入三个空格`

+ 这是一级列表的第一项
   + 这是二级的第一项


## 表格
| 表头 | 表头 |
| ---- | ---- |
| 内容 | 内容 |
| 内容 | 内容 |

## 代码
### 代码行
使用反引号将代码行包裹起来
`This is a C language line`
### 代码块
代码块的前后均使用三个反引号包裹, 且需要单独一行
```
This is the first C language line
This is hte second C language line
```

### 流程图
```flow
st=>start:

