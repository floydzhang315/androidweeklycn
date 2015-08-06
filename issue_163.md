# Issue #163

>原文链接：[http://androidweekly.net/issues/issue-163](http://androidweekly.net/issues/issue-163)

>[点击订阅邮箱](http://tinyletter.com/androidweeklycn)第一时间掌握 Android Weekly 中文版更新动态

## 文章 & 教程

**[使用 RecyclerView 控件来进行拖拽](https://medium.com/@ipaulpro/drag-and-swipe-with-recyclerview-6a6f0c422efd)** (medium.com)  
这篇文章会在之前的文章的基础上进行扩展，增加了对网格布局的支持，“处理”初始化拖拽，显示选中的视图，并且自定义拖拽的动画。

**[Prism 基本组成 － 第 2 部分](https://blog.stylingandroid.com/prism-fundamentals-part-2/)** (blog.stylingandroid.com)   
Mark Allison 将会继续他的 Prism 系列文章 － 一个全新的动态的 Android 主题类库。

**[压榨你的 Gradle 构建](http://saulmm.github.io/squeezing-gradle-builds/)** (saulmm.github.io)
Saúl Molinero 会分享一些关于 Gradle 的 提示和技巧。


Dude, Where's My char[]? (corner.squareup.com)
When Android M preview 2 was released, there were reports of LeakCanary crashing when parsing heap dumps. LeakCanary reached into the char array of a String object to read a thread name, but in Android M that char array wasn't there anymore!

**[Dude, 我的 char 数组在哪里？](https://corner.squareup.com/2015/07/dude-wheres-my-char.html)** (corner.squareup.com)
当 Android M 预览版 2 发布的时候，有关于 LeakCanary 在解析堆打印的时候会崩溃的报道。LeakCanary 会到一个 String 对象的字符串数组里面去读一个线程的名字，但是在 Android M 里面那个字符数组根本不存在 ！

**[Glide - Yelp 的 Android 应用加载图片](http://engineeringblog.yelp.com/2015/07/glide-how-yelps-android-app-loads-images.html)** (engineeringblog.yelp.com)
在 Yelp 的工程师已经探索出一些并行下载并且处理多图片问题的解决方案，并且最终决定 Glide 将会提供一个有着高性能，简单易用，并且强健特征的方案。

**[我关于 Android 单元测试的定论](https://plus.google.com/+MatthiasK%C3%A4ppler/posts/8sBUyYyRXfn)** (plus.google.com)
Matthias 关于 Android 单元测试的定论：这都 2015 年了，但还是有一点糟糕。虽然不像以前那样糟糕，但是在一些基本的方面还是有一些糟糕。

**[Android 设计扩展类库概况](http://code.tutsplus.com/articles/overview-of-the-android-design-support-library--cms-24234)** (code.tutsplus.com)
Paul Trebilcox-Ruiz 提供了一个形象的关于 Android 设计扩展类库里面控件的概况。


**[如何测试手表界面](http://blog.sqisland.com/2015/07/how-to-test-a-watch-face.html)** (blog.sqisland.com)
Chiu-Ki Chan 创建了一个 Android Wear 手表界面，这个界面根据你那天走了多少步，来用不同的猫显示时间。像这种东西怎样测试呢？

**[当 InstaMaterial 遇到设计扩展类库](hhttp://frogermcs.github.io/instamaterial-meets-design-support-library/)** (frogermcs.github.io)
在这篇文章中，作者更新了他的从谷歌提供的材料设计类库实现的自定义视图 InstaMaterial 的源代码。


**[做一个基于 TDD 的 HackerNews 安卓客户端](http://www.philosophicalhacker.com/2015/07/17/making-a-tdd-based-hackernews-client-for-android/)** (www.philosophicalhacker.com)
这篇文章（可能以后会有续集）分享了一些基于 TDD 工作流程的开发一个 Hacker News 客户端应用的方法。

**[安卓数据绑定：再见 Presenter ，你好 ViewModel](http://tech.vg.no/2015/07/17/android-databinding-goodbye-presenter-hello-viewmodel/)** (tech.vg.no)
这个作者用 Hannes Dorfmann 的从他的 Ted Mosby 框架的说明，通过谷歌新的数据绑定，阐述了从 MVP 到 MVVM 的变化。
