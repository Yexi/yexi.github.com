Markdown & Reveal.js   
了解一下
<br/>  
2018.05.27
---
为什么要了解Makrdown & Reveal.js
--
![](https://media2.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif)
--
![](https://media2.giphy.com/media/cfuL5gqFDreXxkWQ4o/giphy.gif)
---

Markdown是啥
--
>Markdown是一种轻量级标记语言，它允许人们“使用易读写的纯文本格式编写文档，然后转换成有效的XHTML（或者HTML）”。这种语言吸收了很多在电子邮件中已有的纯文本标记的特性。
>
> ————维基百科   

--
>Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。
> ————百度百科

---
Markdown的优点
* 简单，容易上手（易读，易写，易修改）
* 纯文本实现，容易扩展，方便和其他工具联通
* 平台支持广：以**github、Stack Overflow**未售的各种平台，各种博客都支持，现在也有越来越多的网站支持，国内有**CSDN、博客园、简书、有道云笔记等**
* 丰富的工具链
    * 编辑器：各种支持所见即所得的编辑器
    * 和各种其他格式互相转换的工具：PDF、Mobi、Equb、HTML等等

---
### 编辑器及推荐
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
一款简单，高效并且优雅的markdown编辑器，它提供了一种所见即所得的全新的markdown写作体验。
---
### 标题  
\# 一级标题  
\## 二级标题  
\### 三级标题  
\#### 四级标题  
\##### 五级标题  
\###### 六级标题
--
### 空格与换行
* 空格：使用`&#160;`
* 空行: 使用&lt;br/&gt;
--
### 列表
* 无序列表：  
在文字前面加上`＋`或者`*`  
\＊ 1  
\＊ 2  
\＊ 3
<br />
* 有序列表：  
在文字前加`1.` `2.` `3.`  
--
### 引用
如果你需要引用一小段别处的句子，那么就要用引用的格式，只需要在文本前面加上`>`
--
### 粗体和斜体
* 用两个*或两个_包含一段文本就是粗体的语法  
* 用一个*或一个_包含一段文本就是斜体的语法
--
### 图片与链接
插入链接与插入图片的语法很像,    
区别在于一个!号   <br />
图片为: ![]\(ImageUrl\)  
链接为: []\(\)
--
### 代码块和表格
Markdown的代码块可使用\`\`\`包围或tab键  
---
Reveal.js又是个啥
--
* 一个使用 HTML 轻松创建精美的演示文稿框架
* Reveal.js 配备了广泛的功能，包括嵌套幻灯片，Markdown 内容，PDF 导出，演讲笔记和 JavaScript API。还有一个全功能的可视化编辑器和平台：slides.com。
--
![](https://cdn.sspai.com/2017/08/29/73673b91c30fda95a3e628d07d2bd17c.gif?imageMogr2/quality/95/thumbnail/!700x233r/gravity/Center/crop/700x233)
---

完整版安装：<br>
安装Node.js  安装Grunt   
```
git clone https://github.com/hakimel/reveal.js.git
```
到reveal.js文件夹，安装依赖
```
cd revael.js
npm install
```
运行
```
grunt serve
```


--

--
再见Word！你好Markdown!
再见PPT!你好Reveal.js!
--
＃ 谢谢大家
--


https://vxhly.github.io/2016/09/reveal-js-cn-document/
