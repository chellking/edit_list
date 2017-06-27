# edit_list


[toc] 目录1
[toc] 目录2

### 标题

还可增加二、三、四、五、六级标题，总共六级
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

### 粗体和斜体
用两个 ** 包含一段文本就是粗体的语法 **

用一个 * 包含一段文本就是斜体的语法 *

### 高效绘制 流程图、序列图、甘特图、表格

#### 流程图：
```
graph TD
A[Christmas] -->B(Go shopping)
B --> C{Let me think}
```

### 代码高亮

``` java
class SomeClass：
pass
>>> message = ''' interpreter

```

### 制作待办事项To-do List

- [x] 已经完成项目1
- [x] 已经完成事项1
- [x] 已经完成事项2
- [ ] 待办事项1
- [ ] 待办事项2


### 列表
注：-、1.和文字之间要保留一个字符的空格。

#### 无序列表

- 列表1
- 列表1.1
- 列表1.2
- 列表2
- 列表3

#### 有序列表

1. 列表1
1. 列表1.1
2. 列表1.2
2. 列表2
3. 列表3


### 引用

> 记录，成为更好的自己。---有云

### 表格

|header1 | hedader2|
|---|---|
|row1 col1 | row1 col2|
|row2 col1 | row2 col2|

** github格式 **

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

### 分割线

这是第一段内容
***
这是第二段内容

### 连接与图片

#### 插入链接

[超级连接](http://github.com/iuap3)

#### 插入图片
![这是个图片](http://)



语法
===

1. 标题

书写方式: ##、### + 空格 + 内容

\## 大标题
\### 小标题
\#### 超小标题

超大标题   //等于号写于文字下方
\===
标题      //同超大标题
\---

ps: 标题左侧空格不必须,但是如果是要上传到github作为文章的话,则必须要有.

2.行内代码

\`这个符号在1的左边\`
这个符号在1的左边

3. 引用

书写方式: >、> > + 空格 + 内容

A.单层引用

>第一行>开头+两个空格换行
第二行不必再写>
效果

第一行>开头+两个空格换行 第二行不必再写>
B.叠层引用


> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.
效果

This is the first level of quoting.

This is nested blockquote.
Back to the first level.

4. 列表

A.无序列表

书写方式 *、-、+ + 空格 + 内容

* Red
* Green
* Blue

- Red
- Green
- Blue

+ Red
+ Green
+ Blue
效果:(三种方式效果一样)

Red
Green
Blue
Red
Green
Blue
Red
Green
Blue
B.有序列表

书写方式 数字 + 空格 + 内容

 1. 这是第一个
 1. 这是第二个
 1. 这是第三个
效果:(会自动排序)

这是第一个
这是第二个
这是第三个

5. 分割线

书写方式: ***、---、\n +> + \n

* * *
***
*****
- - -
---
效果:



6. 超链接

书写方式: [title](href)


[markdown-syntax](http://daringfireball.net/projects/markdown/syntax)
效果

markdown-syntax
以变量的方式定义超链接 
书写方式[var_name]: url "title"

[id]: http://example.com/  "Optional Title Here"
This is [an example][id] reference-style link.
效果:

This is an example reference-style link.

7. 强调(加粗，斜体)

书写方式: *内容*、**内容**、_内容_、__内容__,

*内容*
**内容**
_内容_
__内容__
效果:

内容 
内容 
内容 
内容

8. 图片引用

书写方式:![alt](图片路径)


![这是张图片](/path/to/im)
效果:

这个跟超链一样都可以设置定义变量

[id]: url/to/image  "Optional title attribute"
![hahah][id]
效果



9. 杂项

A.简单超链接

<http://example.com/>
效果:

http://example.com/
B.简单email地址

<xiazhichao75@126.com>
效果:

xiazhichao75@126.com

10. 代码块

书写方式:四个空格 or Tab

    四个空格
    一个tab
效果:

四个空格
一个tab
心得
因为之前看过SF的markdown解释器的语法规则，当时我想，这都是markdown，语法应该都一个样吧，结果照着SF的语法规则，行不通。下面我就来列一列他们之间的有哪些是不一样的

引用的换行
SF的换行规则是另起一行+`>`

GP的换行规则是在一行末尾+两空格`  `+回车不必+`>`
SF无法引用超大标题,为了让你们看到效果，我才截的图,当然这可能没什么卵用
分割线的使用方法，
SF是---,***中间不可加空格
GP是可以在中间插空格的
SF无法将<xiazhichao75@126.com>解释成email
新手驾到，如有不足之处，还请指点，大家共同进步。