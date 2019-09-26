
Markdown & Reveal.js   
了解一下
<br />   
@叶翔  
2018.05.25
--
![](res/fun1.gif)
--
![](res/fun2.gif)
---
Markdown是啥
--
* Markdown是一种轻量级标记语言，它允许人们“使用易读写的纯文本格式编写文档，然后转换成有效的XHTML（或者HTML）”。这种语言吸收了很多在电子邮件中已有的纯文本标记的特性。  ————维基百科

* Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。  ————百度百科

--
Markdown是由**Aaron Swartz**和**John Gruber**共同设计.  
+ John Gruber是苹果社群著名的blogger、作家、UI设计师、软件工程师,持续观察和发表苹果公司相关资讯和观点长达十余年。  
<br />
+ Aaron Swartz就是那位于2013年1月11日自杀,有着开挂一般人生经历的程序员。维基百科对他的[介绍](http://zh.wikipedia.org/wiki/%E4%BA%9A%E4%BC%A6%C2%B7%E6%96%AF%E6%B2%83%E8%8C%A8)是：软件工程师、企业家、作家、政治组织者和互联网黑客主义者，他参与了网上信息源发布格式RSS和Markdown的开发，还是知识共享的组织者，也是网站框架web.py的设计者，同时他在社交媒体Reddit收购其公司Infogami后成为它的合伙人。
---
Markdown的优点
* 简单，容易上手（易读，易写，易修改）
* 纯文本实现，容易扩展，方便和其他工具联通
* 平台支持广：以**github、Stack Overflow**未售的各种平台，各种博客都支持，现在也有越来越多的网站支持，国内有**CSDN、博客园、简书、有道云笔记等**
* 丰富的工具链
    * 编辑器：各种支持所见即所得的编辑器
    * 和各种其他格式互相转换的工具：PDF、Mobi、Equb、HTML等等

---
### 工欲善其事，必先利其**器**
--
* **Windows** 平台
    * [MarkdownPad](http://markdownpad.com/)
* **Linux** 平台
    * [ReText](http://sourceforge.net/p/retext/home/ReText/)
* **Mac** 平台
    * [Mou](http://mouapp.com/)
* **IOS** 平台
    * Byword
* **Android** 平台
    * MarkdownX
* **在线编辑器**
    * [CmdMarkdown](https://www.zybuluo.com/mdeditor)
--
* [Sublime Text 3](http://www.sublimetext.com/3)
一款代码编辑器，也是HTML和散文先进的文本编辑器。
<br/>
* ***[Atom](https://atom.io/)***
一款由**Github**打造的先进的开源跨平台编辑器。
<br/>
* **[Typora](https://typora.io)**
一款简单，高效并且优雅的Markdown编辑器，它提供了一种所见即所得的全新的Markdown写作体验。
---
### 标题  
+ \# 一级标题  
+ \## 二级标题  
+ \### 三级标题  
+ \#### 四级标题  
+ \##### 五级标题  
+ \###### 六级标题
--
### 粗体与斜体
* 用两个*或两个_包含一段文本就是粗体的语法  
* 用一个*或一个_包含一段文本就是斜体的语法
--
### 换行与引用
* 换行: 使用&lt;br/&gt;
* 如果你需要引用一小段别处的句子，那么就要用引用的格式，只需要在文本前面加上`>`
--
### 列表
* 无序列表：  
在文字前面加上`＋`或者`*`  
\+ 1  
\+ 2  
\+ 3
<br />
* 有序列表：  
在文字前加数字点`1.` `2.` `3.`
--
### 图片与链接
插入链接与插入图片的语法很像,区别在于一个!号   <br />
* 图片为: ![]\(ImageUrl\)  
* 链接为: []\(\)
--
### 代码块与表格
* Markdown的代码块可使用\`\`\`包围或tab键
* 表格:表格的写法很简单，跟表格的形状很相似 ，表格的对齐方式:我们可以指定表格的单元格对齐方式，冒号在左边表示左对齐，右边表示右对齐，两边都有就表示居中
--
### 流程图   
1. 进入流程图的编辑模式:flow关键字
2. 定义流程图元素:定义流程图有六个基本的元素
```
tag＝>type: content:url  
 =>start //开始框,
 =>end //结束框,
 =>inputoutput //输出输入框,
 =>condition //条件选择框,
 =>operation //操作处理框,
 =>subroution //子流程  
 ```
3. 连接好定义的元素
```
tag1->tag2->tag3
```
--
### 其他
balabala...
--
> 当你读或者写用HTML标签标记的文字时，这些标记在强迫你集中注意力去思考他们。而我希望Markdown格式的文本所传达的是一种感觉.
————John Gruber

---
Reveal.js又是个啥
--
![Reveal.js](https://upload-images.jianshu.io/upload_images/16777-450adc0c3346b29d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/700)  

一个展示内容的HTML框架
--
### 优点  
* 制作简单
* 运行简单
* 功能强大，灵活：Reveal.js 有多套默认皮肤，支持 多种PPT切换动画，Fragments，内联PPT( nested slides)，代码高亮，解析 Markdown，懒加载图片和视屏，导出为PDF和一系列的 JS API 等特性
---
![](https://cdn.sspai.com/2017/08/29/73673b91c30fda95a3e628d07d2bd17c.gif?imageMogr2/quality/95/thumbnail/!700x233r/gravity/Center/crop/700x233)
--
1. 安装Node.js
2. 安装Grunt  
3. 使用git命令行或者直接到github下载reveal.js
```
git clone https://github.com/hakimel/reveal.js.git
```
4. 到reveal.js文件夹
```
cd reveal.js
```
5. 安装依赖  
```
npm install
```
6. 运行
```
grunt serve
```
--
Reveal.js文件夹结构
* css/ 核心样式文件
* js/ 核心 JavaScript 文件
* plugin/ 为 reveal.js 开发的组件
* lib/ 所有其它第三方的资源 (JavaScript, CSS, fonts)
--
内部Markdown  
* 在index.html里面找到```<div class="slides">```标签，删除节点内的内容，如果是直接使用Markdown   
```
<section data-markdown>
    <script type="text/template">
        ## 带你上车
        这是一个[教学](https://yexiang.me)
    </script>
</section>
```  
--
外部Markdown  
* 你可以将你的内容写到一个单独的文件中然后在运行的时候让 reveal.js 去加载
```
<section data-markdown="example.md"
  data-separator=""
  data-separator-vertical=""
  data-charset="utf-8">
</section>
```
---
相关链接：
+ **翔哥的分享:http://yexiang.me**
+ [Markdown语法说明](http://wowubuntu.com/markdown/)
+ [Reveal.js中文文档](https://vxhly.github.io/2016/09/reveal-js-cn-document/)
---
## 感谢大家！
## 周末愉快～
--
