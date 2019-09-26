Flutter入坑分享
<br />
![flutter](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1568970684076&di=36900fd9beb6274d2783401ffa8cd596&imgtype=0&src=http%3A%2F%2Fpic4.zhimg.com%2Fv2-3fe15f21a33caa34d3fd9129ca1e1e2f_b.jpg)
<br />   
@Yx  
2019.09.26
---
* Flutter是Google的开源UI框架，Flutter生成的程序可以直接在Google最新的系统Fuschia上运行，也可以build成apk在Android上运行，或是生成ipa在iOS运行，最近发布的Flutter1.9版本，Flutter web支持现已成功合并到Flutter的主分支.
Flutter团队正在扩展Flutter，支持创建macOS、Windows和Linux应用程序。开发者只需使用同一套基准代码，便可为移动平台、桌面端和网页端开发应用。

---
![flutter_framwork](\flutter_framework.png)
--
* Engine层实现了Flutter的渲染引擎、文字排版、事件处理及Dart运行时等功能
* Framework层则是一个用Dart实现的UI SDK，包含了动画、图形绘制和手势识别等功能。
--
为什么Flutter选择了Dart？
* 谷歌亲儿子，据说是因为Dart项目组就在flutter隔壁而被选上的。
* Dart是Google推出的一门编程语言，最初是希望取代Javascript运行在浏览器端，后来。。。
* Dart运行时和编译器支持两种Flutter关键特性的结合：基于JIT(Just In Time:边运行边编译)和hot-reloads（热重载）能够缩减开发周期，加之AOT(Ahead Of Time:运行前编译)编译器生成的高效ARM代码， 能够为产品部署提供快速启动能力和可预期的性能指标。
---
* Material:中文名：材料设计语言，是由Google2014年推出的设计语言，谷歌表示，这种设计语言旨在为手机、平板电脑、台式机和“其他平台”提供更一致、更广泛的“外观和感觉”。Material就是Android风格的组件。
https://material.io/
* Cupertino: 库比蒂诺是硅谷核心城市之一，也是苹果公司的总部，这就很容易理解了，Cupertino就是iOS风格的组件。
---
![flutter_widget](https://image-static.segmentfault.com/108/204/1082044781-5bb9ca2f76968)
--
* Widget是flutter功能的抽象描述，是视图的配置信息，同样也是数据的映射，是Flutter开发框架中最基础的概念。前端框架中常见的名词，比如视图(View)、视图控制器(View Controller)、活动（ACtivity）、应用（Application）、布局（layout）等，在Flutter中都是Widget。
--
![flutter_framwork](\demo_time.jpg)
---
![flutter_framwork](\flutter_study.jpg)
---
相关链接：
+ **我的分享:http://yexiang.me**
+ [Flutter 开发文档](https://flutter.cn/docs)
---
## 感谢聆听！

