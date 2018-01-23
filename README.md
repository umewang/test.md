# 大标题
[![License](https://img.shields.io/badge/license-BSD-blue.svg)](LICENSE)


这是一篇根据**CaffeOnACL**的.md文件改写的示例文档

**CaffeOnACL**在github上的网址为 [OAID/CaffeOnACL](https://github.com/OAID/CaffeOnACL)

### 小标题
* 项目符号示例
* 项目符号示例
* 项目符号示例



使用```(也是tab键上面的符号键)格式化代码段，而不是单引号

```

Hello,world!

```


**插入图片** 

找不到可用的公司Logo，所以随便找了张
![example](https://raw.githubusercontent.com/umewang/test.md/master/example.jpg)

---
#语法参考说明

#Standard Markdown

##Strong and Emphasize
```
*emphasize*   **strong**
_emphasize_   __strong__
```
##Links and Email
Inline:
```
An [example](http://url.com/ "Title")
```
Reference-style labels (titles are optional):
```

An [example][id]. Then, anywhere
else in the doc, define the link:

  [id]: http://example.com/  "Title"
```
Email:
```
An email <example@example.com> link.
```

##Images
Inline (titles are optional):
```
![alt text](/path/img.jpg "Title")
```
Reference-style:
```
![alt text][id]

[id]: /url/to/img.jpg "Title"
```
##Headers
```
Setext-style:

Header 1
========

Header 2
--------
```
atx-style (closing #’s are optional):
```
# Header 1 #

## Header 2 ##

###### Header 6
```
##Lists
Ordered, without paragraphs:
```
1.  Foo
2.  Bar
```
Unordered, with paragraphs:
```
*   A list item.

    With multiple paragraphs.

*   Bar
```
You can nest them:
```
*   Abacus
    * answer
*   Bubbles
    1.  bunk
    2.  bupkis
        * BELITTLER
    3. burper
*   Cunning
```
##Blockquotes
```
> Email-style angle brackets
> are used for blockquotes.

> > And, they can be nested.

> #### Headers in blockquotes
> 
> * You can quote a list.
> * Etc.
```
##Inline Code
```
`<code>` spans are delimited
by backticks.

You can include literal backticks
like `` `this` ``.
```
##Block Code
Indent every line of a code block by at least 4 spaces or 1 tab.
```
This is a normal paragraph.

    This is a preformatted
    code block.
```
##Horizontal Rules
Three or more dashes or asterisks:
```
---

* * *

- - - -
```
##Hard Line Breaks
End a line with two or more spaces:
```
Roses are red,   
Violets are blue.```

