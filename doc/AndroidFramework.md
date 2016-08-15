# Android Framework

1. Android Framework在Android系统架构中的作用？  
Android系统从上往下分为应用层、框架层、核心库+运行时，linux层。其中Framework层向上提供Java接口，封装了应用开发需要的API；向下通过JNI接口调用core lib逻辑，并最终作用到硬件；通过java管理c++，简化内存等管理逻辑，让开发者能通过Java API专注于业务开发；框架从包括了AMS、WMS等核心实现，其中采用C/S架构的方式提供系统服务支持业务开发。

## 知识点  

1. SystemServer  
2. Handler-Message-Looper  
3. Activity 和 Service  
4. Fragment  
5. View  
6. MotionEvent  
7. LayoutInflator  
8. android.util.*  
9. Context  
10. ClassLoader  
11. Binder  
12. WMS，AMS，PMS，NMS，IMS 等系统 Service

## 关联阅读  
1. [《Android Framework如何学习，从应用到Framework层怎么平稳过度?》](http://www.jianshu.com/p/14daa5ffcc36)  
    * "Android的功夫，在Android之外",先明确问题，例如“如何实现进程间的通讯”；然后从问题演进的源头去理解，“Linux中进程间通讯的方式”，最后学习Android中Binder的实现方式。

2. [《阅读 ANDROID 源码的一些姿势》](http://kaedea.com/2016/02/09/android-about-source-code-how-to-read/)  
    * 一些推荐的文章和博客，以及知识点
