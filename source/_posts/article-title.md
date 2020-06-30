---
title: article title
date: 2020-06-29 11:11:00
tags:
---
## 这是一个练习hexo建博客的测试  
-----------------
# 练习markdowm文本格式（汇总记）  
一标题：
#号，几个井号就是几级标题 -符号（二级）及=符号（一级）在文字下面做单独一行，且有直线分割  
二段落及格式：
两空格+回车或空行间隔（可以看到两种效果出现的间隔行宽不同）

文字格式

字体：斜体：前后加*或_     、粗体：前后加**或__ 、粗斜体：前后加***或___
分隔线：三个以上*或_（中间可以用空格间隔）
* * * *
_____________
删除线：在文字两侧加~~  
~~没生效哇~~  

下划线： <u>标签</u>  
脚注：[^如此]

 
***********************
列表： 
无序表：*加空格 +加空格 -加空格
有序表：数字加.
嵌套表： 子列表选项前添加4个空格  
1. 贰万伍仟
    * dfsfs

**********************
区块：  (注意空格) 可以跟列表搭配使用
> 一  
> - 或者温热温热（发现这一行是需要与上一行上下配合使用的）  
> > csfsdfs  

****
代码：1. 段落中 用反引号包起来 `printf（）`
2. 代码块 使用四个空格或一个tab（制表符） 或```加选定语言（可不选）包围  
    <?php
	echo>  
	
```javascript
$(document).ready(function () {
    alert('RUNOOB');
});
```  
*************
链接：
[链接名称](链接地址)
或者
<链接地址>
<https://www.runoob.com>  

高级链接：
变量来设置一个链接，变量赋值在文档末尾进行：
这个链接用 1 作为网址变量 [Google][1]
这个链接用 runoob 作为网址变量 [Runoob][runoob]
然后在文档的结尾为变量赋值（网址）

  [1]: http://www.google.com/
  [runoob]: http://www.runoob.com/
--------
  图片：  
  ![图片1](http://static.runoob.com/images/runoob-logo.png)（方式一）  
  ![图片2](http://static.runoob.com/images/runoob-logo.png "RUNOOB") (方式二 双引号中是悬停的title)  
  
  这个连接图片[runoob][q]
  然后在文档的结尾为变量赋值（网址）
  [q]: http://static.runoob.com/images/runoob-logo.png
  （方式三 跟链接一样 html没成功）  
  设定宽高：使用< img>标签
  <img src="http://static.runoob.com/images/runoob-logo.png" width="20%">
  
  -----------
  表格：(预览没成功，转成html后成功)
  竖线分隔列
  表头与其他行用---分隔  
  -: 设置内容和标题栏居右对齐。
 :- 设置内容和标题栏居左对齐。
 :-: 设置内容和标题栏居中对齐。  
 
|表头|表头|
|----|----|
|单元格|单元格|
|单元格|单元格|
  
| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :---: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |
**********
其他特性：
1.支持使用html标签元素
目前支持的 HTML 元素有：< kbd> < b> < i> < em> < sup> < sub> < br>等 
例：
使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑  
2.反斜杠转义符号
Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号：

\   反斜线
`   反引号
*   星号
_   下划线
{}  花括号
[]  方括号
()  小括号
 #   井字号
+   加号
-   减号
.   英文句点
!   感叹号  
3.数学公式：
使用两个美元符 $$ 包裹 TeX 或 LaTeX 格式的数学公式来实现（会转成数学形式的格式，没出来）  
$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
${$tep1}{\style{visibility:hidden}{(x+1)(x+1)}}
$$
----
THE END
 