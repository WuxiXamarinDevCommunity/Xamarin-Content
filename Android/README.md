# Android 学习之路


## IDE

- [Android Studio](https://developer.android.com/studio/)

    - `Android Studio` 是一个为 `Android` 平台开发程序的集成开发环境, 可供开发者免费使用。 并在Windows、OS X和Linux平台上均可运行.

- [Visual Studio](https://visualstudio.microsoft.com/xamarin/)
  - [Installing Xamarin in Visual Studio 2017](https://docs.microsoft.com/en-us/xamarin/cross-platform/get-started/installation/windows)
  - `Xamarin` 是一个跨平台开发软件，通过使用 `C＃` 共享的代码库，开发人员可以使用 `Xamarin` 工具，使用本地用户界面编写原生的 Android、iOS和Windows 应用程序，并跨多个平台（包括Windows和MacOS）共享代码

## Android 模拟器

Android emulator runs too slowly if hardware acceleration is not available on the computer that runs it.

You can drastically improve the performance of the Android emulator by using special x86 virtual device images in conjunction with the virtualization features of your computer.


More information, please refer to:  [Hardware acceleration for emulator performance (Hyper-V & HAXM)](https://docs.microsoft.com/en-us/xamarin/android/get-started/installation/android-emulator/hardware-acceleration?pivots=windows)

## 翻墙

- 能 Google， Android 技能等级 +1

## Google Android官方教程

- [Android Training Course in Chinese](http://hukai.me/android-training-course-in-chinese/index.html)

## Android 基础

- [Android体系架构](http://gityuan.com/2015/08/01/android-arvchitecture/)
- [Android四大基本组件介绍与生命周期](http://www.cnblogs.com/bravestarrhu/archive/2012/05/02/2479461.html)
- [Activity](https://developer.android.com/reference/android/app/Activity)
    - [Android系统用于Activity的标准Intent](https://blog.csdn.net/zhangjg_blog/article/details/10901293)
        - Intent解决了Android中四大组件的通讯，非常有用，这篇博客收集整理了系统的标准Intent
    - [Activity与Service生命周期](http://gityuan.com/2015/05/31/android-lifecycle/)
    - [两分钟彻底让你明白Android Activity生命周期(图文)](https://blog.csdn.net/android_tutor/article/details/5772285)
- [Service](https://developer.android.com/guide/components/services?hl=en-us)
  - [Android Service完全解析，关于服务你所需知道的一切(上)](https://blog.csdn.net/guolin_blog/article/details/11952435)
  - [Android Service完全解析，关于服务你所需知道的一切(下)](https://blog.csdn.net/guolin_blog/article/details/9797169)
  - [Android Service使用详解](https://www.jianshu.com/p/95ec2a23f300)
  - [关于Android Service真正的完全详解，你需要知道的一切](https://blog.csdn.net/javazejian/article/details/52709857)
- [Broadcasts](https://developer.android.com/guide/components/broadcasts)
  - [Android四大组件：BroadcastReceiver史上最全面解析](https://blog.csdn.net/carson_ho/article/details/52973504)
  - [Android BroadcastReceiver使用详解](https://www.jianshu.com/p/f348f6d7fe59)
- [Content providers](https://developer.android.com/guide/topics/providers/content-providers?hl=en-us)
  - [Android：关于ContentProvider的知识都在这里了！](https://blog.csdn.net/carson_ho/article/details/76101093)
- [Android UI](https://developer.android.com/guide/topics/ui/) 
  - [ListView的基本使用与优化](http://www.cnblogs.com/noTice520/archive/2011/12/05/2276379.html)
  - 算了，不写了。内容太多，建议仔细查看文档
- [Notification](https://developer.android.com/guide/topics/ui/notifiers/notifications?hl=en-us)
  - [A Notification Demo](https://github.com/ZLOVE320483/Notification/)
  - [NotificationChannel 适配填坑指南](https://www.jianshu.com/p/99bc32cd8ad6)
  - [Android Oreo 通知新特性，这坑老夫先踩了](https://zhuanlan.zhihu.com/p/32930310)
  - [Android Notification的使用](https://www.jianshu.com/p/ec67ba83934a)
  - [**Android通知栏微技巧，8.0系统中通知栏的适配**](https://blog.csdn.net/guolin_blog/article/details/79854070)
  - [Android O(8.0)通知栏适配](https://blog.csdn.net/rentee/article/details/78303532)
- [Android 屏幕适配](https://developer.android.com/guide/practices/screens_support?hl=en-us)
  - [Android 屏幕适配：最全面的解决方案](https://www.jianshu.com/p/ec5a1a30694b)
  - [一种极低成本的Android屏幕适配方式](https://zhuanlan.zhihu.com/p/37199709)
  - [Android屏幕适配全攻略(最权威的官方适配指导)](https://blog.csdn.net/zhaokaiqiang1992/article/details/45419023)
- [Android 中 SQLite 应用详解](https://blog.csdn.net/liuhe688/article/details/6715983)
- [Styles and Themes](https://developer.android.com/guide/topics/ui/look-and-feel/themes)
    - [Android开发之Theme、Style探索及源码浅析](https://blog.csdn.net/yanbober/article/details/51015630)
- [Permission](https://developer.android.com/guide/topics/permissions/overview)
  - [Request App Permissions](https://developer.android.com/training/permissions/requesting?hl=en-us)
- File System
  - [Android 中的内部存储与外部存储](https://blog.csdn.net/u012702547/article/details/50269639)
  - [FileProvider Overview](https://developer.android.com/reference/android/support/v4/content/FileProvider)
  - [关于 Android 7.0 适配中 FileProvider 部分的总结](http://yifeng.studio/2017/05/03/android-7-0-compat-fileprovider/)
  - [Android 7.0 行为变更 通过FileProvider在应用间共享文件](https://blog.csdn.net/lmj623565791/article/details/72859156)
  - [Android FileProvider的使用](https://blog.csdn.net/Next_Second/article/details/78585745)
- [Resources](https://developer.android.com/guide/topics/resources/providing-resources?hl=zh-cn#Accessing)
- [AndroidManifest.xml](https://developer.android.com/guide/topics/manifest/manifest-intro?hl=zh-cn)
- Android View 的工作原理
  - [事件分发机制](https://blog.csdn.net/xyz_lmn/article/details/12517911)
  - [一个很好的讲解自定义 View 的 blog](https://blog.csdn.net/lfdfhl/article/details/51671038)
- Android 消息机制
  -  [Handler详解系列—— Handler异步消息机制详解(附图)](https://blog.csdn.net/lfdfhl/article/details/40016165)
- [Android进程生命周期与ADJ](http://gityuan.com/2015/10/01/process-lifecycle/)
- [Android Context完全解析](https://blog.csdn.net/guolin_blog/article/details/47028975)
- [**ANR**](https://developer.android.com/topic/performance/vitals/anr)
  - [Android ANR：原理分析及解决办法](https://www.jianshu.com/p/388166988cef)
  - [理解Android ANR的触发原理](http://gityuan.com/2016/07/02/android-anr/)
- **OOM**
  - [浅析android的OOM问题](https://www.jianshu.com/p/ee78eb0fb651)   
  - [Android OOM案例分析](https://tech.meituan.com/oom_analysis.html)
  - [Android避免OOM（内存优化）](https://www.jianshu.com/p/f5d8d3066b36)
  - [Android内存泄漏的八种可能（上）](https://www.jianshu.com/p/ac00e370f83d)
- Android 开源框架
  - [Android常用库之遇见你真舒心](https://www.jianshu.com/p/19368c2cdcaf)
  - [2017 Android GitHub 常用开源框架汇总](https://blog.csdn.net/QDJdeveloper/article/details/75074600)
  - 博客只做示例
- [APP优化](http://gityuan.com/2015/09/26/App-optimize1/)
  - [Android性能优化的方方面面](https://www.jianshu.com/p/b3b09fa29f65)
  - [性能优化的几大考虑(有些 Android 开发基础再看)](https://github.com/Piasy/notes/blob/master/Android-Java/AndroidPerformancePatterns.md)
- Android Crash
  - [Android开发之打造永不崩溃的APP——Crash防护](https://www.jianshu.com/p/01b69d91a3a8)
  - [Cockroach](https://github.com/android-notes/Cockroach)
  - [Recovery --> a crash recovery framework](https://github.com/Sunzxyong/Recovery)
  - [Android 平台 Native 代码的崩溃捕获机制及实现](http://www.10tiao.com/html/330/201707/2653579163/1.html)
  - [Android进阶——Crash异常捕获并发送到服务器](https://blog.csdn.net/qq_30379689/article/details/53731646)
  - [理解Android Crash处理流程](http://gityuan.com/2016/06/24/app-crash/) 
- [Android 热启动&冷启动](https://developer.android.com/topic/performance/vitals/launch-time)
  - [Android App 冷启动优化方案](https://juejin.im/post/5aec28bb6fb9a07ac90d13dc)
  - [Avoiding cold starts on Android](http://saulmm.github.io/avoding-android-cold-starts)
  - [一触即发 App启动优化最佳实践](https://www.jianshu.com/p/672d9bbbf684)


## Android 进阶

思考

- [Android 系统/手机 有哪些好?](https://www.zhihu.com/question/37801069/answer/97391748)
- [****如何自学Android？****](https://zhuanlan.zhihu.com/p/20708611)
- [Android 进阶之路](https://blog.csdn.net/u011240877/article/details/68939826)
- [你和高级工程师的差距在哪里？](https://zhuanlan.zhihu.com/p/21960033)

开发技巧

- [Android 开发规范](http://gityuan.com/2015/08/10/android-arch-coding-style/)
- [Android Studio 常用快捷键](http://gityuan.com/2015/08/08/android-studio-shortcut/)
- [adb常用命令笔记](http://gityuan.com/2015/06/28/adb-notes/)
- [Git常用命令](http://gityuan.com/2015/06/27/git-notes/)


书籍

- [深入理解 Android 内核设计思想](https://www.oschina.net/question/2720166_2254666)
- [**Android 开发艺术探索**](https://www.zhihu.com/question/36115286)
- [深入剖析 Android 新特性](https://www.oschina.net/question/2720166_2280238)

Android

- [Android Instant Apps](https://developer.android.com/topic/google-play-instant/)
  - [什么是安卓Instant App(即时App)?](https://code.tutsplus.com/zh-hans/tutorials/what-are-android-instant-apps--cms-29283)
  - [Android Instant App --> Hello World project]()
  - [Google 版小程序 Instant Apps，到底怎么样？](https://zhuanlan.zhihu.com/p/27044515)
- [Android事件分发机制](http://gityuan.com/2015/09/19/android-touch/)
- [理解ContentProvider原理](http://gityuan.com/2016/07/30/content-provider/)
- [四大组件之BroadcastRecord](http://gityuan.com/2017/06/03/broadcast_record/)
- [Android Broadcast广播机制分析](http://gityuan.com/2016/06/04/broadcast-receiver/)
- [startActivity启动过程分析](http://gityuan.com/2016/03/12/start-activity/)
- [startService启动过程分析](http://gityuan.com/2016/03/06/start-service/)
- [NotificationManagerService原理分析](http://gityuan.com/2018/03/03/notification/)


**非常赞的文章**

- [**Android系统开篇**](http://gityuan.com/android/)
- [全面剖析SharedPreferences](http://gityuan.com/2017/06/18/SharedPreferences/)

## Android 高阶

- [Android耗电统计算法](http://gityuan.com/2016/01/10/power_rank/)
- [AMS之dumpsys篇](http://gityuan.com/2017/07/04/ams_dumpsys/)
- [性能工具Traceview](http://gityuan.com/2016/01/17/traceview/)
- [性能工具Systrace](http://gityuan.com/2016/01/17/systrace/)
- [Android调试技巧](http://gityuan.com/2017/07/11/android_debug/)
- [Binder概述](http://gityuan.com/2014/01/01/binder-gaishu/)
- [Binder系列—开篇](http://gityuan.com/2015/10/31/binder-prepare/)
- [为什么 Android 要采用 Binder 作为 IPC 机制？](https://www.zhihu.com/question/39440766/answer/89210950)
- [Android源码开发环境搭建](http://gityuan.com/2016/08/13/android-os-env/)
- [Android中为什么主线程不会因为Looper.loop()里的死循环卡死？](https://www.zhihu.com/question/34652589/answer/90344494?from=profile_answer_card)