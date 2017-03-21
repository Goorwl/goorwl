# 橙子小站：Android技术汇总【持续更新中...】

欢迎大家  FORK , STAR , 提 ISSUES 和 SUGGEST , 共同进步...

[Android开发谷歌中文网站](
https://developer.android.google.cn/index.html)

## 目录
* [Android常用博客](#多媒体编程)
* [Android常用网站](#Android常用网站)
* [Android开发](#Android开发)
	* [Android多媒体开发](#Android多媒体开发)
	* [Android数据存储](#Android数据存储)
	* [Android网络访问](#Android网络访问)
	* [Android第三方框架](#Android第三方框架)
* [常用API网站](#常用API网站)

## 正文

### Android常用博客
* [郭霖](http://blog.csdn.net/guolin_blog)
* [鸿洋_](http://blog.csdn.net/lmj623565791)
* [严振杰
](http://www.yanzhenjie.com/#/)
* [任玉刚](http://blog.csdn.net/singwhatiwanna)
* [stormzhang](http://stormzhang.com/)
* [xiaanming](http://blog.csdn.net/xiaanming)
* [亓斌](http://blog.csdn.net/qibin0506)
* [梁肖技术中心](http://liangxiao.blog.51cto.com/all/3626612)
* [未完待续。。。](http://www.jianshu.com/u/26d7cc9f08cb)
### Android常用网站
* [泡在网上的日子](http://www.jcodecraeer.com/plus/list.php?tid=16)
* [Android源码下载](http://androidxref.com/)
* [干货集中营](http://gank.io/)
* [Android开发中文](http://www.androidchina.net/)
* [MD中文翻译](http://wiki.jikexueyuan.com/project/material-design/)
* [推酷](http://www.tuicool.com/)
* [美团点评技术团队](http://tech.meituan.com/)
### Android开发
#### Android多媒体开发
* 音频开发
	* [Android 音频技术开发总结](https://yq.aliyun.com/articles/8637#)【博文】
* 图片加载库
	* [fresco](https://github.com/facebook/fresco)【框架】
		* Facebook 开源的图片加载框架；优点：三级缓存，流式(渐变式显示图片)，支持GIF。
	* [Glide](https://github.com/bumptech/glide)【框架】
		* Google 员工的开源项目，2014年Google I/O大会推荐；优点：实现缓存，支持优先级，与Activity生命周期一致。
		* 使用介绍博文：[-Android图片加载框架最全解析-](http://blog.csdn.net/guolin_blog/article/details/53759439)
	* [picasso](https://github.com/square/picasso)【框架】
		*  Square 的开源项目，维护者 JakeWharton；优点：自带统计，支持优先级，支持延迟加载，根据网络情况自动调节并发数。
	* [图片框架原理分析及性能比对](http://www.trinea.cn/android/android-image-cache-compare/)【博文】
	* [图片框架的基本比较及用法](http://www.jianshu.com/p/ada9b90fa9e6)【博文】
* 视频库
	* [ijkplayer](https://github.com/Bilibili/ijkplayer)【框架】
	* [VLC](https://wiki.videolan.org/AndroidCompile)【框架】
	* [ffmpeg](https://www.ffmpeg.org/)【框架】
	* [vitamio](https://www.vitamio.org/)【框架】
	* [Android视频开发简介](http://www.jianshu.com/p/8436c7353296)【博文】
#### Android数据存储
* 数据库
	* [Litpal](https://github.com/LitePalFramework/LitePal)【框架】
		* 作者郭霖大神，轻量级的数据库框架，只需要简单的配置即可使用数据库常用功能，1.5版本支持线程切换。目前还在维护并且开发新功能。
		* litepal使用介绍推荐看郭大神 [-Android数据库高手秘籍系列-](http://blog.csdn.net/guolin_blog/article/details/38461239)
	* [GreenDAO](https://github.com/greenrobot/greenDAO)【框架】
		* 由 greenrobot 公司开源并对其维护，该公司还有一款著名的开源产品 EventBus；优点：运行效率高，内存消耗少，性能佳。官方测试：[性能报告](http://greendao-orm.com/features/) 配置稍显麻烦，但是适合大型数据操作。
		* greenDAO使用介绍: [-简书博客系列-](http://www.jianshu.com/p/320f43081d12)
#### Android网络访问
* [okhttp](https://github.com/square/okhttp)【框架】
	* square 公司开发的网络访问框架，用处很广泛，已经得到 Google 官方认可。
	* 使用介绍博文：[OkHttp使用教程](http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2015/0106/2275.html)
* [NoHttp](https://github.com/yanzhenjie/NoHttp)【框架】
	* 开发者严振杰，据说比 retrofit 更简单，和RxJava完美结合，支持五种缓存模式，支持断点下载等。
	* 使用介绍，官方地址就有具体介绍。
* [retrofit](https://github.com/square/retrofit)【框架】
	* square 公司的，和RxJava搭配更好用哦。
	* 使用介绍博文：[Retrofit用法详解](http://blog.csdn.net/duanyy1990/article/details/52139294) 和 [-Retrofit使用教程系列-](https://www.zybuluo.com/xujun94/note/479910)
* [Volley](https://developer.android.com/training/volley/index.html)【框架】
	* Android开发团队推出的网络请求框架。可以进行网络访问，也可以加载网络图片，性能优化很好，适用于访问频繁但是数据量不大的网络请求。
	* 使用介绍博文： [-Android Volley完全解析系列-](http://blog.csdn.net/guolin_blog/article/details/17482095)
#### Android第三方框架
* [EventBus](https://github.com/greenrobot/EventBus)【框架】
	* greenrobot 公司的又一款力作，事件总线。主要在于组件间通讯，简单易用。并且使得事件发布和订阅充分解耦。
	* 使用介绍博文：[EventBus介绍](http://www.cnblogs.com/angeldevil/p/3715934.html) 和 [EventBus 3.0 简单使用介绍](http://www.jianshu.com/p/348f0ff6ab01)
* [dagger2](https://github.com/google/dagger)【框架】
	* square 开源，之后由 Google 公司维护，主要作用用于代码之间的解耦。
	* 使用介绍博文：[dagger2使用小结Demo](https://github.com/luxiaoming/dagger2Demo)
* [butterknife](https://github.com/JakeWharton/butterknife)【框架】
	* JakeWharton 作品。主要使用注解减少findViewById的书写。
	* 使用介绍博文：[BUTTERKNIFE--VIEW注入框架](https://stormzhang.com/openandroid/android/2014/01/12/android-butterknife/)
* [RxAndroid](https://github.com/ReactiveX/RxAndroid)【框架】
	* ReactiveX 开发维护，响应式编程，大大简化代码，优化逻辑。
	* 使用介绍博文：[给 Android 开发者的 RxJava 详解](https://gank.io/post/560e15be2dca930e00da1083) 和 [-RxJava系列-](http://www.jianshu.com/p/ec9849f2e510)

## Android实用工具
### 常用工具网站	
* [友盟+](http://message.umeng.com)
	* 提供：APP使用统计，消息推送，社会化分享等；
* [bmob后端云](http://www.bmob.cn/)
	* 提供：云数据库，短信验证码，移动支付等；
* [Mob](http://www.mob.com/)
	* 提供：社会化分析，短信验证码，常用API等；
* [极光](https://www.jiguang.cn/)
	* 提供：推送，IM，短信，统计等功能；
### 常用API网站
* [阿里云](https://market.aliyun.com/products)
* [API大全](http://apis.io/)
* [免费json接口](http://www.bejson.com/knownjson/webInterface/)
* [聚合数据](http://free.juhe.cn/)
* [webxml](http://www.webxml.com.cn/zh_cn/index.aspx)
* [豆瓣电影](https://developers.douban.com/wiki/?title=guide)
* [国内值得关注的官方 API 集合](https://zhuanlan.zhihu.com/p/25121768)

### Android热修复
* [Android 热修复专题](https://zhuanlan.zhihu.com/p/25863920)【博文】

### Android多渠道打包	
* [新一代开源Android渠道包生成工具Walle](http://tech.meituan.com/android-apk-v2-signature-scheme.html)


### [持续更新。。。](http://www.jianshu.com/u/26d7cc9f08cb)