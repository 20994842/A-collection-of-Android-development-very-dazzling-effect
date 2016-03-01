# A-collection-of-Android-development-very-dazzling-effect
安卓开发中非常炫的效果集合，效果看博客http://www.cnblogs.com/ldq2016/p/5217590.html
 安卓开发中非常炫的效果集合

这几天开发的时候，想做一些好看而且酷炫的特效，于是又开始从网上收集各种特效资源。下面给大家一些我喜欢的把，附代码，喜欢的看源代码，然后加到自己项目去把！！

 

所有效果Dome下载地址：https://github.com/20994842/A-collection-of-Android-development-very-dazzling-effect
1.很简单却很酷的粒子破碎效果

这里写图片描述
介绍：
实现思路

1.新建一个 Bean Particle，表示一个粒子对象；新建一个 View ExplosionField作为画布用来显示破碎的粒子；新建一个属性动画（ValueAnimator） ExplosionAnimator用来改变不同时刻的粒子状态；

2.通过View生成图片Bitmap，把生成的图片分解成若干个粒子，让每个粒子记录特定的位置，所有的粒子组合能看出是原图。

3.加上动画效果，使得点击View后，粒子能有所变化。

4.构思算法，形成不一样的效果。
2.AVLoadingIndicatorView各种加载效果

这里写图片描述

介绍：
AVLoadingIndicatorView各种加载效果，适合做加载loading动画效果。
里面代码封装挺不错的，直接可以拷贝使用想要的loading效果。
3.PercentageBar自定义动态柱形图

这里写图片描述
介绍：
实现：通过自定义PercentageBar实现，很酷炫把
4.MaterialPowerMenu 点击按钮切换页面加载呈现效果

这里写图片描述
各种好看的弹出框，吓死你
5.android加载框效果

这里写图片描述

android加载框效果，本例子有几种效果弹出dialog,本例子主要自定义SVProgressHUD 类，
本例子来源：https://github.com/saiwu-bigkoo/Android-SVProgressHUD
6.android市面主流侧滑框架

这里写图片描述
android市面主流侧滑框架，本架构主要实现侧滑出现底部view和首页实现tabhost效果，并且每一个fragment支持使用多个 viewpager,很好的处理viewpager一次全部加载问题，可以根据viewpager出现的时候调用初始化页面，提高性能。这是一个不错的架 构，欢迎android小伙伴们一起学习。
本项目主要底部TabFragment和左边侧滑DragLayout 以及CustomViewPager 实现，并且提供退出应用的一种关闭所有acitiviy的方式。
7.各种android弹出dialog效果以及各种dialog样式

这里写图片描述
各种android弹出dialog效果以及各种dialog样式大全，项目中包含十多种dialog样式和风格，以及弹出和退出效果。本文就只放一张Gif图意思一下吧！
8.WilliamChart各种图表效果实现大全

这里写图片描述
WilliamChart各种图表效果实现大全，有水平线条表格，有柱状表格等。
9.几种常用Android Progress效果

这里写图片描述
几种常用Android Progress效果，本例子自定义ProgressWheel，CustomClipLoading，PieProgress三个特效的进度条，
通过本例子可以学习如何自定义控件，效果挺不错，适合各种网络加载使用。
每一个控件大概实现原理：
CustomClipLoading 继承FrameLayout，通过布局引入view然后添加到addView(view);
ProgressWheel 和 PieProgress 都是 继承 View通过 onDraw（）在画布Canvas不断画出效果，可以通过本例子学习如何使用OnDraw()方法。
10.高仿QQ空间 侧滑Menu效果且换肤功能

这里写图片描述
高仿QQ空间 侧滑Menu效果并且提供换肤功能，本项目大体结构是
首先有一个换肤基类BaseSkinActivity，然后其他activity都继承这个基类，
类中提供com.zhy.changeskin.SkinManager.getInstance().changeSkin()更改皮肤 .
11.HeartLayout 类似吹泡泡效果

这里写图片描述
介绍：
HeartLayout 类似吹泡泡效果,自定义HeartLayout 添加addHeart(),
12.DragExpandGrid可展开，可拖动，可排序，可删除，固定更多的GridView

这里写图片描述
介绍：
DragExpandGrid可展开，可拖动，可排序，可删除，固定更多的GridView,展开合并支持动画,支持箭头图标移动。
数据的处理和显示使用Bean,来自于500彩票Andorid客户端首页功能。
13.ShareAnim带动画的分享效果

这里写图片描述
介绍：
ShareAnim带动画的分享效果,本例子只展示弹出页面的效果
和点击取消的时候对话框消失的效果。但是没有添加分享功能和扫码功能的代码，
14.PathEffectTextView写字效果

这里写图片描述
介绍：
PathEffectTextView一个写字的效果，自定义PathTextView，其中通过
ObjectAnimator.ofFloat(this, “phase”, 0.0f, 1.0f).setDuration(3000); mSvgAnimator.start();
设置动画，通过SparseArray 来实现，这个例子是5.0以及以上的。
15.TimelyAnimation 超酷计时器

这里写图片描述
介绍：
Euclid ListView滑动和点击进去其他页面特效，通过SwingLeftInAnimationAdapter
实现每一个item点击和滑动进入详细页面的动画效果，提供getViewAnimator()方法。
16.AmapDemo仿照一号专车的地图界面

这里写图片描述
介绍：
AmapDemo仿照一号专车的地图界面，地图加载定位进入后的放大效果和地图移动效果非常棒，
本项目指导我们如何使用地图功能，如何自定义系统定位蓝点，本项目主要引导我们如何嵌入
第三方sdk实现地图定位效果。
17.vectalign-samples变形动画

这里写图片描述
介绍：
我们知道4.4以后AnimatedVectorDrawable可以让两个SVG图像无缝过渡（称为变形动画），
但是这两个svg图像的path必须参数个数要相等，同时这些参数的类型要匹配（也就是说格式要对齐），
如果不对齐会产生异常。简单的path可以手动修改对齐，但是复杂点的就比较难了。
这个工具就是通过命令行的方式将任意两个svg资源转换成对齐的模式，而不会改变原始图像的外观。
18.ArrowDownloadButton下载按钮从点击到下载完成特效

这里写图片描述
介绍：
ArrowDownloadButton下载按钮从点击开始下载到下载完成各个阶段有不一样的特效展示，
自定义一个ArrowDownloadButton然后监听点击事件setOnClickListener（）在onClick（）
里面 button.startAnimating();然后再按钮里面启动一个定时器Timer 定时更新按钮进度
button.setProgress(progress);
19.AnimLikeSougou仿搜狗输入法

这里写图片描述
介绍：
说明：Android Animtaion 仿搜狗输入法的精品市场 一键安装dialog弹出效果
，具体可以看这篇blog:

来源：https://github.com/teffy/AnimLikeSougou
20.android-ripple-background

这里写图片描述
能产生波浪效果的背景图片控件，可以自定义颜色，波浪扩展的速度，波浪的圈数。
https://github.com/skyfishjy/android-ripple-background
21.A-Z字母排序和过滤搜索功能

这里写图片描述
介绍：
Android 实现ListView的A-Z字母排序和过滤搜索功能，实现汉字转成拼音 。

https://github.com/leerduo/SortListView
22.下拉刷新的自定义布局

这里写图片描述
介绍：
一个实现了下拉刷新的自定义布局，动画效果不错。

https://github.com/tuesda/CircleRefreshLayout
23.水滴效果的下拉刷新，效果非常不错。

这里写图片描述

介绍：
水滴效果的下拉刷新，效果非常不错。

https://github.com/recruit-lifestyle/WaveSwipeRefreshLayout
24.在安卓系统中引入了模拟纹波效应

这里写图片描述
介绍：
在安卓系统中引入了模拟纹波效应

https://github.com/siriscac/RippleView
25.实现guillotine-styled 动画效果

这里写图片描述
介绍：
提供了一种实现guillotine-styled 动画效果的简单方法，效果很赞的，Yalantis公司越来越厉害了。

https://github.com/Yalantis/GuillotineMenu-Android
26.动画效果非常生动的菜单

这里写图片描述
介绍：
https://github.com/linroid/FilterMenu

动画效果非常生动的菜单，是根据dribbble上的概念设计而来：
27.自定义ViewGroup实现的圆形旋转菜单，支持跟随手指旋转以及快速旋转。

这里写图片描述
介绍：
自定义ViewGroup实现的圆形旋转菜单，支持跟随手指旋转以及快速旋转。

https://github.com/hongyangAndroid/Android-CircleMenu
28.Side-Menu.Android

这里写图片描述
介绍：
https://github.com/Yalantis/Side-Menu.Android
29.类似星球大战字幕效果的TextView

这里写图片描述
介绍：
类似星球大战字幕效果的TextView
30.两个不同的数字之间无缝切换效果

这里写图片描述
介绍：
两个不同的数字之间无缝切换效果，可以用在时间显示之类的应用中

https://github.com/adnan-SM/TimelyTextView
31.一个简单的带动画效果的饼状图。

这里写图片描述
介绍：
一个简单的带动画效果的饼状图。

https://github.com/Geek-1001/MagnificentChart
32.帅气Toast

这里写图片描述
介绍：
介绍：默认的toast很丑，而且也没有真正提供显示短暂消息的功能。这个库能为toast显示动画反馈，显示到选择按钮或者删除按钮的过度动画。而且toast 的生命周期是完全取决于你的。

项目地址： https://github.com/code-mc/loadtoast
33.高仿新版58 加载动画

这里写图片描述
介绍：
https://github.com/zzz40500/android-shapeLoadingView
高仿新版58 加载动画
34.Material Calendar View

这里写图片描述
介绍：
介绍：一个Material风格的日历视图，其中日历月视图是使用GridLayout实现的

来源： https://github.com/prolificinteractive/material-calendarview
35.挺赞的带进度动效Button

这里写图片描述
介绍：
带有动效进度的Button，个人感觉挺喜欢的。
36.FrescoDemo

这里写图片描述
介绍：
一个基于Android Design library使用Fresco来加载图片的Demo项目。
