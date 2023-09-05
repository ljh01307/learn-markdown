# Markdown
是一种轻量级标记语言，它以纯文本形式(易读、易写、易更改)编写文档，并最终以HTML格式发布。 Markdown也可以理解为将以MARKDOWN语法编写的语言转换成HTML内容的工具。

## 优点：

它是易读（看起来舒服）、易写（语法简单）、易更改纯文 本。处处体现着极简主义的影子。
兼容HTML，可以转换为HTML格式发布。
跨平台使用。
越来越多的网站支持Markdown。
更方便清晰地组织你的电子邮件。（Markdown-here, * Airmail）
摆脱Word（我不是认真的）。
## 缺点：

1、需要记一些语法（当然，是很简单。五分钟学会）。
2、有些平台不支持Markdown编辑模式。

> 注：本文的显示效果用的是TyporaMarkdown编辑软件

### 一、标题
在想要设置为标题的文字前面加#来表示 一个#是一级标题，二个#是二级标题，以此类推。支持六级标题。

注：标准语法一般在#后跟个空格再写文字。

示例：

# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题

或者，在文本下方的行上，添加任意数量的==（标题级别1）或 --（标题级别2）的字符。

这是一级标题
===============

这是二级标题
---------------	

### 二、字体

加粗
要加粗的文字左右分别用两个*号包起来

斜体
要倾斜的文字左右分别用一个*号包起来

斜体加粗
要倾斜和加粗的文字左右分别用三个*号包起来

删除线
要加删除线的文字左右分别用两个~~号包起来

示例：

**这是加粗的文字**
*这是斜体的文字*`
***这是斜体加粗的文字***
~~这是加删除线的文字~~

### 三、引用
在段落的每行或者只在第一行使用符号>,还可使用多个嵌套引用，

示例：

>这是引用的内容
>>这是引用的内容
>>>>>>>>>>这是引用的内容

### 四、分割线

三个或者三个以上的 - 或者 * 或者_都可以。

示例：

---
----
***
*****
___
____


可以看到，显示效果是一样的。

### 五、图片
1）插入互联网上图片

语法：

![图片描述](图片链接 ''图片title'')

图片描述就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。
注意：title可加可不加
注意：这个图片描述可以不写。

示例：

![雾山五行](https://p6.itc.cn/images01/20200728/d5aba3834b134dfe878cafc576715b85.jpeg   "雾！山！五！行！")

2）插入本地图片链接

语法：

![图片描述](图片本地路径 ''图片title'')
图片描述就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。
注意：title可加可不加
注意：这个图片描述可以不写。

### 六、超链接

语法：

[超链接名](超链接地址 "超链接title")
注：title可加可不加
示例：

[知乎](https://www.zhihu.com/)
[百度](https://www.baidu.com/)

### 七、列表

无序列表

语法：
无序列表用 - + * 任何一种都可以

- 无序列表内容
+ 无序列表内容
* 无序列表内容

注意：- + * 跟内容之间都要有一个空格

可以看到，显示效果是一样的。
-----
有序列表语法：
数字加点

1. 有序列表内容
2. 有序列表内容
3. 有序列表内容

注意：序号跟内容之间要有空格
效果如下：


### 八、表格

语法：

|表头|表头|表头|
|---|:--:|---:|
|内容|内容|内容|
|内容|内容|内容|

第二行分割表头和内容。
- 有一个就行，为了对齐，多加了几个
文字默认居左
-两边加：表示文字居中
-右边加：表示文字居右
示例：

|姓名|性别|分数|
|--|:--:|--:|
|小明|男|100|
|小红|女|89|
|小飞|男|88|

### 十一、换行

方法1: 连续两个以上空格+回车

方法2：使用html语言换行标签<br>：

### 十二、缩进字符
推荐使用第三种缩进方式

&nbsp;  缩进1/4中文   

&ensp;  缩进半个中文，一个字符    

&emsp;  缩进一个中文，2个字符    

示例:

&nbsp;你若安好，便是晴天。     

&ensp;你若安好，便是晴天。    

&emsp;你若安好，便是晴天。    

评价一下自己的颜值   

[A.英俊潇洒/倾国倾城](https://baike.baidu.com/item/%E8%87%AA%E6%81%8B%E5%9E%8B%E4%BA%BA%E6%A0%BC%E9%9A%9C%E7%A2%8D/1052308    "真不要脸" )😅    

[B.丑的像屎](https://zhuanlan.zhihu.com/p/250137650    "6" )😞      


