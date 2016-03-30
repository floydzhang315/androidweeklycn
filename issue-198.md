# Issue #198

>

原文链接：<http://androidweekly.net/issues/issue-198>

> [点击订阅邮箱](http://tinyletter.com/androidweeklycn)第一时间掌握 Android Weekly 中文版更新动态

## 文章 & 教程

**[使用 Design 支持库的 Bottom Sheets](http://code.tutsplus.com/articles/how-to-use-bottom-sheets-with-the-design-support-library--cms-26031)**
（code.tutsplus.com)）  
Design 支持库已经随着时间在改进，在 23.2 release 版本增加了 bottom sheets 的支持。在本文中，你会学到如何很简单地利用 bottom sheet 模板实现到你自己的app中。

**[Android 的线程批注的缺点](http://mcomella.xyz/blog/2016/thread-annotations.html)**
（mcomella.xyz）  
当Android的线程注释，如@UiThread和@WorkerThread宣布，Michael Comella 很兴奋。然而，许多个月后，他觉得像他所希望的，但不知道确切的原因注解并没有正常工作。他决定调查原因。

**[AutoValue 的扩展](http://jakewharton.com/presentation/2016-03-08-ny-android-meetup/)**
（jakewharton.com）  
谷歌的AutoValue库通过代码生成提供了方便的Java值类型和其即将发行的有一个强大的新功能：扩展。本讲座介绍了扩展功能，包括为Android实用的扩展功能，并为建立自己的技巧。

**[有关 Vectors 的所有内容（最终版）](https://blog.stylingandroid.com/vectors-for-all-finally/)**
（blog.stylingandroid.com)   
第三次发布临时系列文章，关于 Android VectorDrawable 的状态。Google 发布了 Android 支持库 23.2，包含了很多的其他模块，也包含了倍受瞩目的 VectorDrawableCompat。

**[五个不太知名的挂载主线程的方法](http://blog.nimbledroid.com/2016/03/21/ways-to-hang-main-thread.html)**
（blog.nimbledroid.com)   
在一般情况下，这会导致主线程挂起16 * N 毫秒将导致 N 中的任方法调用丢帧。我们把这种方法叫 挂方法。在这篇博客文章中，我们将首先看看挂起方法的例子，再看看为五个鲜为人知的方式，可能会挂起主线程。

**[开源代码 Android 的 LightCycle](https://developers.soundcloud.com/blog/Open-sourcing-LightCycle-for-Android)**
（developers.soundcloud.com）  
最近 SoundCloud 开源了 LightCycle，一个帮助将逻辑从 Activity 和 Fragment 分离到很小，自包含的组件，名字叫 LightCycles。

**[Felipe Lima 讲述在 Android Airbnb 采用 RxJava](https://realm.io/news/kau-felipe-lima-adopting-rxjava-airbnb-android/)**
（realm.io）  
这此讨论涵盖了 Airbnb 的采用新模式和技术的经验，包括动画、实现难度和过程中的经验教训。RxJava 也在生成环境代码示例中使用，对比势在必行的 reactive 途径，并将讨论了各自的优点和局限性。

**[第一个五年](https://blog.stylingandroid.com/the-first-five-years/)**
（blog.stylingandroid.com）  
Mark Allison 已经通过写每周有深度的文章为我们分享了他的 Andr​​oid 的知识。请一定要感谢他在Twitter上，G +或这篇文章。并聘请他，而他仍然可用！

**[RxJava - 使用 Subjects 的问题](http://tomstechnicalblog.blogspot.com/2016/03/rxjava-problem-with-subjects.html)**
（tomstechnicalblog.blogspot.com）  
Subjects 既是一个 Obserable 也是一个 Observer。某些特性和功能看起来很方便，但是也能快速促使反模式。Thomas Nield 写了一些你可能会遇到的一些问题。

**[高级 RxJava：编写一个自定义的 reactive 基本类型](http://akarnokd.blogspot.com/2016/03/writing-custom-reactive-base-type.html)**
（akarnokd.blogspot.com)   
时而，问题或要求上来，人都会真正想拥有他/她自己的reactive 类型。尽管 RxJava 的 Observable 有大量方法并可以利用lift(),extend() 和 compose()可扩展的，有人觉得 Observable 应该有xyz()操作符，或者在某些链里，链不应该调用uvm()。

## 赞助

**[用 buddybuid 更好更快构建 app](https://buddybuild.com/?ref=androidweekly0307)**
 (buddybuild.com)    
Buddybuild是自动构建，部署和收集反馈您的Andr​​oid应用程序最简单的方法。即时发送应用程序建立以用户buddybuild内置的电子邮件和懈怠根据部署系统。然后，用一个简单的截图，用户可以轻松地与重要的设备元数据给你完美的洞察，他们遇到任何错误一起发送反馈。与buddybuild发货更好的应用程序，更快 - 无需尝试演示在登录！

**[聘请-市场上的Android开发人才招聘](https://hired.com)**
 (hrd.com)    
Android的开发者的需求，所以不宜公司​​适用于你？在录用，这就是它究竟是如何工作的。获得5+的工作机会来自像尤伯杯，条纹，和Facebook与1应用的公司。今天就加入雇佣和获得1K的奖金，当你找到一份工作！

## 设计

**[移动应用设计：吸引用户，并提高转化率](https://www.thinkwithgoogle.com/collections/principles-of-mobile-app-design-engage-users-and-drive-conversions.html)**
（www.thinkwithgoogle.com）  
在一个拥挤的市场，如何应用程序吸引新客户，赢得忠诚度，并创造价值？随着一个愉快的应用体验伟大的设计。

**[Keyline Pushing app + Layout Bound](http://androiduiux.com/2016/03/23/designprotip-keyline-pushing-app-layout-bound/)**
（androiduiux.com）    
Taylor Ling 常常会问他怎么从检查的角度设计的应用程序，特别是在布局，走线，条重要等等，让他分享他的工具和技术在这个岗位。

**[动画设计是UI的未来](https://blog.prototypr.io/motion-design-is-the-future-of-ui-fc83ce55c02f?gi=2b9616dc2ea2#.j9nd6n6yl)**
（blog.prototypr.io）  
小题大做的是什么？为什么是重要的？动画告诉你这些故事。在一个应用中一切都是序列，而动画是你的引导。对于每一个按钮点击和屏幕转换，下面有很多种情况。

**[Android 上的 Bottom Tabs 设计](http://blog.iangclifton.com/2016/03/19/bottom-tabs-on-android/)**
（blog.iangclifton.com）  
鉴于 Android 已经在应用程序顶部显示 tab 的格局，两个明显的原因让那些底部 tab 脱颖而出：在屏幕的底部往往更容易达到一个大的手机上，在底部把卡给设计视觉平衡。

**[UX 手机设计：底部导航](https://uxplanet.org/perfect-bottom-navigation-for-mobile-app-effabbb98c0f?gi=195931fe66cb#.z9wpqrtwa)**
（uxplanet.org）  
根据 Nick Babich 的介绍，把重要的放置顶层而经常使用动作在屏幕的底部，因为它们被舒适地单手或一拇指相互作用达成。

**[Microinteractions：应用设计的秘密](https://uxplanet.org/microinteractions-the-secret-to-great-app-design-4cfe70fbaccf?gi=e628394245ee#.8ji3xgx27)**
（uxplanet.org）  
把最好的产品做好两件事情：特征和细节。特点是什么吸引人们到你的产品。细节是什么让他们在那里。和细节是什么实际上使我们的应用程序从我们的竞争对手中脱颖而出。

## 工作
 
**[移动开发](https://boards.greenhouse.io/khanacademy/jobs/15829?t=2cmief)**
（加州山景城-可以远程）    
Khan Academy 是一个使命，以提供对任何人都是免费的，世界一流的教育，任何地方。见你可以在http://khan.co/ka_stories的影响，来帮助建立应用程序采用了最新的 Andr​​oid 技术（RxJava，Dagger，Retrofit等），提供免费的高质量的学习内容

**[Android开发者](https://boards.greenhouse.io/truemotion/jobs/162254?t=xejy3w)**
（波士顿）    
Censio是塑造互联世界的未来，和拯救生命的过程。我们的数据科学家和工程师正在使用先进的智能传感器技术，大数据和分析，以提高驾驶员的安全，同时重新定义保险是如何定价和交付。

**[资深手机工程师- Android](https://boards.greenhouse.io/rallyhealth/jobs/62243?gh_jid=62243&gh_src=nam4o0)**
（旧金山，加州或华盛顿特区）  
拉力Health公司是一家数字医疗公司，很容易让人们以帮助个人和雇主重新构思消费者健康参与负责他们的健康和健康的。我们正在寻找的人加入我们的Andr​​oid团队！

**[Android 工程师](https://jobs.lever.co/yelp/46136fee-03e6-4766-b6ad-a8b87c0bf9cd?lever-source=Android_Weekly_Newsletter)**
（旧金山）  
Yelp的连接消费者以极大的本地企业都在世界各地。我们正在寻找谁爱数以百万计的人民创造愉快的用户体验，并采取对他们的工作产品的所有权兴旺各级Android开发。

## 库与代码

**[Lightcycle](https://github.com/soundcloud/lightcycle)**
（github.com）	
LightCycle是一个Android库，一个帮助将逻辑从 Activity 和 Fragment 分离到很小，自包含的组件，名字叫 LightCycles。

**[MaterialColorsApp](https://github.com/romannurik/MaterialColorsApp)**
（github.com）	
由 Roman Nurik 开发的一个方便的小 Mac 应用程序，让您可以快速访问标准的材料设计调色板。

**[LandscapeVideoCamera](https://github.com/JeroenMols/LandscapeVideoCamera)**
 (github.com)    
强大的自定义Android相机与在视频质量和文件大小的精细控制，限制录音唯一的风景线。

## 新闻

**[Android的实验I / O挑战 ](https://www.androidexperiments.com/challenge)**
（www.androidexperiments.com）	
在庆祝活动的创意和代码加入谷歌。输入您的Andr​​oid实验现在和4月13日之间，赢得一个机会，它（和你）去谷歌I / O 2016年！

**[Fragmented Podcast Update – TSHIRTS!](http://fragmentedpodcast.com/misc/sol2/)**
（fragmentedpodcast.com）	
在宣布限量版 Fragmented 的T恤。

**[Android Studio 2.1 Preview 4 Available](http://tools.android.com/recent/androidstudio21preview4available)**
（tools.android.com）	
谷歌已经在 canary channel 推出 Android Studio 2.1 预览版4。此版本整合了即时运行更多的bug修复。

## 工具

**[谷歌的新的辅助扫描仪](http://www.androidpolice.com/2016/03/23/googles-new-accessibility-scanner-helps-developers-check-their-apps-for-accessibility-issues/)**
（www.androidpolice.com）	
全新的Accessibility扫描仪应用程序允许你检查潜在的问题或可访问性方面可能的改进您的应用程序。它在Play商店免费下载，但目前它看起来像它仅限于在Android 6.0设备。

## 视频与播客

**[Design notes with Max Ignatyev of Sympli ](http://www.designnotes.fm/all/with-max-ignatyev-of-sympli)**
（www.designnotes.fm）	  
本周利亚姆Spradlin马克斯伊格纳季耶夫，Sympli.io的创始人，该桥梁与Android这样的工作室和X代码IDE来缓解开发人员和设计师之间的合作，如Photoshop和素描的应用程序的工具讲话。




