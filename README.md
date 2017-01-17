学习Abp框架之Mpa实操演练（来了就给个star吧）
>作为.Net工地搬砖长工一名，一直致力于挖坑（Bug）填坑（Debug），但技术却不见长进。也曾热情于新技术的学习，憧憬过成为技术大拿。从前端到后端，从bootstrap到javascript，从python到Node.js，了解过设计模式，也跟风了微信公众号开发。然而却浅尝辄止，未曾深入。买了一本本的技术书籍，没完整的翻完一本。屯了一部部的pdf，却只是在手机里占着内存。想过改变，却从未曾着手改变。
以上算是我程序猿生涯的真实写照。
现在我要尝试改变，从基础的helloworld开始，记下学习中遇到的芝麻小事，循序渐进，只为沉淀厚积而薄发。

这个系列，是我对DDD系列框架的一次从零开始的尝试。
在开始本系列之前，建议通读[Abp中文文档](https://www.gitbook.com/book/darkcraft/abpdocument2chinese/details)；
如果英文功底不错，请直接查看[官方文档](http://www.aspnetboilerplate.com/Pages/Documents)。

当然，博客园也有大神的总结，很值得一阅，在此感谢大神们的分享总结。
* [基于DDD的现代ASP.NET开发框架--ABP系列文章总目录](http://www.cnblogs.com/mienreal/p/4528470.html) --阳光铭睿
* [一步一步使用ABP框架搭建正式项目系列教程](http://www.cnblogs.com/farb/p/ABPPracticeContent.html)--tbk至简
* [ABP教程-打造一个《电话簿项目》-目录-MPA版本-基于ABP1.13版本](http://www.cnblogs.com/wer-ltm/p/5776069.html) --角落
* [ABP源码分析：整体项目结构及目录](http://www.cnblogs.com/1zhk/p/5268054.html) --HK Zhang
* [ABP文档 - 目录](http://www.cnblogs.com/kid1412/p/5971838.html)（持续更新翻译的abp中文文档） -- kid1412

本系列文章主要是基于ABP模板开发**Mpa**（多页面）项目。
由于是入门系列，不会用到代码生成器，每一行代码都是手动敲入。
源码已上传至[Github-LearningMpaAbp](https://github.com/yanshengjie/LearningMpaAbp)，可自行参考。
本系列基于持续总结，会持续更新，请关注学习。
 
『任务清单』的主要功能是完成对任务的创建分配，简单的增删改查。

**目录**

[ABP入门系列（1）——使用Abp框架开发Mpa『任务清单』](http://www.jianshu.com/p/a6e9ace79345)

[ABP入门系列（2）——通过模板创建MAP版本项目](http://www.jianshu.com/p/a1b5334c5805)

 [ABP入门系列（3）——领域层创建实体](http://www.jianshu.com/p/fde465ae599d)

[ABP入门系列（4）——领域层定义仓储并实现](http://www.jianshu.com/p/6e90a94aeba4)

[ABP入门系列（5）——创建应用服务](http://www.jianshu.com/p/da69ca7b27c6)

[ABP入门系列（6）——展现层实现增删改查](http://www.jianshu.com/p/620c20fa511b)
