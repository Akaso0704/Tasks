# Tasks
Something for tasks.

[提问的智慧](https://github.com/Akaso0704/Tasks/blob/main/README.md#1-%E6%8F%90%E9%97%AE%E7%9A%84%E6%99%BA%E6%85%A7)  
[关于Markdown的学习](https://github.com/Akaso0704/Tasks/blob/main/README.md#2-%E5%85%B3%E4%BA%8Emarkdown%E7%9A%84%E5%AD%A6%E4%B9%A0)  
[Git基本命令](https://github.com/Akaso0704/Tasks/blob/main/README.md#1-git%E5%9F%BA%E6%9C%AC%E5%91%BD%E4%BB%A4)  
[Git建立本地仓库的多种方式](https://github.com/Akaso0704/Tasks/blob/main/README.md#2git%E5%BB%BA%E7%AB%8B%E6%9C%AC%E5%9C%B0%E4%BB%93%E5%BA%93%E7%9A%84%E5%A4%9A%E7%A7%8D%E6%96%B9%E5%BC%8F)   
[关于HTML的学习](https://github.com/Akaso0704/Tasks/blob/main/README.md#%E5%85%B3%E4%BA%8Ehtml%E7%9A%84%E5%AD%A6%E4%B9%A0)
# 第一部分    

***

## 1. 提问的智慧

* 黑客们喜欢回答真正有兴趣且愿意主动解决问题的人的问题. 

* 提问前, 主动去寻找答案(搜索引擎,相关论坛等), 形成一定的解决问题的思路. 

* 提问时, 在内容上:1. 表达出自己为解决问题做出了哪些努力; 2. 简化问题，并且明确表达问题与需求，去除无意义的部分; 3. 不要使用令人反感的字眼; 4. 可以使用"目标--差异"式的结构;

* 在态度上: 1.  有礼貌地提问;      2.  尽管是新手也不要低声下气.

## 2. 关于Markdown的学习  
### 1. Markdown基本语法

1.  使用半角标点, 即英文标点(在标点后加上空格，符合规范且更美观)； 

2.  标题

    "#"加上空格放在标题前, 多少级标题就输入多少个“#”;

3.  斜体字

    两边加"*"或"_";

4.  强调

    两边加"**"或"__";

5.  删除线

    两边加"~~";

6.  代码

    两边加"`";

7. 代码块

   上下加"```";

8.  引用

    ">"加空格放于被引用部分之前(">"数量多的引用被嵌套于其数量少的引用中)；

9. 链接

   文本放于"[]"中, 链接放于"()"中;

10. 分割线

    连续三个"*"或"-"或"_"并回车.

(部分快捷键可以在Typora页面的"段落"中找到)
# 第二部分

***

## Git的学习

### 1. Git基本命令

![示意图](https://www.runoob.com/wp-content/uploads/2015/02/git-command.jpg)

|    命令    |               意义               |
| :--------: | :------------------------------: |
|  git init  |            仓库初始化            |
| git remote |        对远程仓库进行操作        |
|  git push  |       把文件上传至远程仓库       |
| git clone  |         将远程仓库"克隆"         |
|  git pull  |           下载远程代码           |
| git status | 查看有变化的文件及当前的仓库状态 |
| git commit |      将暂存区上传至本地仓库      |

### 2.Git建立本地仓库的多种方式

1. 使用Git GUI Here

   单击鼠标右键找到"Git GUI Here", 再点击"Create New Repository", 找到"Browse"点击后选择一个文件夹, 最后点击"Create"创建完成.

2. 使用Git Bash Here

   单击鼠标右键找到"Git Bash Here", 输入"git init", 建立完成.
# 第三部分
***
> ## 关于HTML的学习
### 1. HTML的认识
*  HTML是一种标记语言, 包括了许多标签. 它不是编程语言，能够"告诉"浏览器如何构造网页, 浏览器根据此呈现网页, 其中有一部分用css.  
* 大多数起始标签(Opening tag)由<>包括一个或一串关键字构成,  结束标签(Closing tag)由<>包括住slash(即/)加上标签内容构成(标签内的元素名不区分大小写). 
* HTML元素由起始标签开始到结束标签结束. 大多数元素可以嵌套. 

### 2. HTML基本构成
```HTML
<!DOCTYPE html>
<html>
    <head>
          <title>balabala</title>
    </head>
    <body>
          <p>bananananana</p>
    </body>

</html>
```

### 3. HTML标签(部分)
|          类别           |     标签      |                             作用                             |
| :---------------------: | :-----------: | :----------------------------------------------------------: |
|      标题(Heading)      |  &lt;h1&gt;| 规定标题的级别. HTML有六个级别的标题, 是多少级标题, 就将h后的数字改成几 |
|                        |&lt;title&gt;| 其中为标题内容 |
|     段落(Paragraph)     |   &lt;p&gt; |                        其中为文本内容                        |
|       链接(Link)        |   &lt;a&gt;  |                 用于添加链接, 跳转至其他网页                 |
| 水平线(Horizontal line) |    &lt;hr&gt;   |                           划分段落                           |
|    定义(definition)     |&lt;html&gt;|              定义文档类型为html, 也被称为根元素              |
|                         |&lt;body&gt; |                         定义主体内容                         |
|                         |&lt;head&gt;|定义文档信息. 包含的是浏览器需要的信息, 如标题, 说明, 关键字, 图标等|
|     字体(Typeface)      |  &lt;b&gt;  |                             加粗                             |
|                         |   &lt;i&gt;  |                             斜体                             |
| 排版布局 | &lt;div&gt; | 类似于矩形框架, 里面可以放置多种内容 |

#### 补充
&lt;a href="输入网址" &gt;赋予网址的文本&lt;/a&gt;

&lt;hr&gt;没有结束标签. 

### 4. 块级元素与内联元素

* 块级元素负责整体方面，总是独占一行，并且高度, 宽度, 内边距, 外边距可以改变. 
* 内联元素和相邻的内联元素在同一行, 高度, 宽度, 内边距, 外边距不可改变. 



## 参考资料 
[MDN](https://developer.mozilla.org/zh-CN/docs/Web/HTML)


