# 概述 
 此博客初衷是记录一下自己开发过程后使用到或者收集到的一些轮子和开源项目，不追求全，只追求实用吧。会不断的更新,也是希望能继续完善吧。
 **推荐**  
 [Github最全面的Android开源项目汇总](https://github.com/Trinea/android-open-project#%E5%8D%81%E4%BA%8Cflipview) 
 <!-- more -->	




 # 功能框架
 **网络请求**
- [OkHttpUtils](https://github.com/jeasonlzy0216/OkHttpUtils)
基于Okhttp的Api的使用封装。Api简洁实用。功能也非常全面。
 
 
----

**数据库**

- [ORMLite](http://blog.csdn.net/lmj623565791/article/details/39122981)
- [GreenDaoMaster](http://blog.csdn.net/krislight/article/details/9391455)

 
框架对比
[ORMLitehe和greenDaoMaster简单性能对比](http://blog.csdn.net/u012565107/article/details/21546829)

 ----

**图片加载**

- [ImageLoader](https://github.com/nostra13/Android-Universal-Image-Loader)
  ImageLoader是目前Android平台上使用数量最多也是最为常见的图片加载框架。
  使用讲解:http://blog.csdn.net/github_25928675/article/details/46442037
- [picasso](https://github.com/square/picasso)
  Picasso是美国一家支付公司Square推出的。它的特点是通过复杂的压缩来减少内存的消耗,自带内存和硬盘的二级缓存
  使用讲解:http://blog.csdn.net/github_25928675/article/details/46660179
- [Fresco](https://github.com/facebook/fresco)
  Fresco是FaceBook推出的一款图片加载框架。自动释放内存。
  使用讲解:http://fresco-cn.org/docs/index.html
  
  
  
  
  
框架对比
[Stackoverflow几个框架对比](http://stackoverflow.com/questions/29363321/picasso-v-s-- imageloader-v-s-fresco-vs-glide) 
[MDCC 2015:三大图片缓存原理、特性对比](http://www.csdn.net/article/2015-10-21/2825984)





 --- 
 
**工具类**
 - [LogUtil](https://github.com/pengwei1024/LogUtils)
 支持直接打印数据集合,如List、Set、Map、数组
 - [DroidFix](https://github.com/bunnyblue/DroidFix)
 热修复的工具,修改补丁

  
**插件**
- [folding-plug](https://github.com/dmytrodanylyk/)
  布局文件分组

**依赖注入**
- [xUtils的Viewutils](https://github.com/wyouflf/xUtils)
 
---
   
 
 # View
  
 
 ## Loading
 - [MetaballLoading](https://github.com/dodola/MetaballLoading)
 水滴传递的效果
![](https://raw.githubusercontent.com/dodola/MetaballLoading/master/metaball.gif)
 - [WhorlView](https://github.com/Kyson/WhorlView)
 漩涡风格的加载效果
![](http://www.jcodecraeer.com/uploads/150818/1-150QP34Q2261.gif)
 - [AVLoadingIndicatorView](https://github.com/81813780/AVLoadingIndicatorView)
 Android Loading动画的一个集合
 ![](https://raw.githubusercontent.com/81813780/AVLoadingIndicatorView/master/Demo.gif)
 - [android-shapeLoadingView仿58loading效果](https://github.com/zzz40500/android-shapeLoadingView)
 ![](https://camo.githubusercontent.com/575b98a56c5546043ec045d044429590e4a623fe/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f3136363836362d376434313538646532636534306139612e676966)




 ## ViewPager
  - [SpringIndicator](https://github.com/chenupt/SpringIndicator)
 viewapger指示器，像水滴流动的效果
  ![](https://raw.githubusercontent.com/chenupt/SpringIndicator/master/img/si_1.0.0.gif)
 - [ProductTour](https://github.com/matrixxun/ProductTour)
 ViewPager的PageTransformer切换动画
 ![](https://raw.githubusercontent.com/matrixxun/ProductTour/master/art/run.gif)
 - [VerticalVie向上滑动的viewpager,没有衔接效果()wPager](https://github.com/kaelaela/VerticalViewa没有衔接效果
![](https://raw.githubusercontent.com/kaelaela/VerticalViewPager/master/art/default.gif)

 ## 指示器
- [FlycoTabLayout](https://github.com/H07000223/FlycoTabLayout)
包含两种TabLayout.[SlidingTabLayout是基于[PagerSlidingTabStrip](https://github.com/jpardogo/PagerSlidingTabStrip)的大量修改，新增了很多自定义的功能。CommonTabLayout:不同于SlidingTabLayout对ViewPager依赖,它是一个不依赖ViewPager可以与其他控件自由搭配使用的TabLayout.
![](https://raw.githubusercontent.com/H07000223/FlycoTabLayout/master/preview_1.gif)

 ## Dialog
 - [FlycoDialog](https://github.com/H07000223/FlycoDialog_Master)
 多种样式与动画效果的对话框
![](https://raw.githubusercontent.com/H07000223/FlycoDialog_Master/master/gif/preview_1.gif)
 




 ## ListView
 - [瀑布流](https://github.com/bavariama1/ListBuddies)
 - [IndexView](https://github.com/Waylenw/Android-UI-Effect#listindex)
 索引控件可拖动，可根据列表滚动移动
 ![](https://raw.githubusercontent.com/Waylenwang/AndroidUI_Waylen/master/screenpic/indexView.gif)
 - [SwipeMenuListView(右滑删除)](https://github.com/baoyongzhang/SwipeMenuListView)
 ![](https://raw.githubusercontent.com/baoyongzhang/SwipeMenuListView/master/demo3.gif)
 
 


 ## 侧滑菜单
- [DragLayout 使用 support.v4 包下的 ViewDragHelper 实现 QQ5.0 侧滑](https://github.com/BlueMor/DragLayout)
![这里写图片描述](https://raw.githubusercontent.com/BlueMor/DragLayout/master/screenshots/123.gif)
- [FlowingDrawer(具有弹性的侧滑菜单)](https://github.com/mxn21/FlowingDrawer
)
![这里写图片描述](http://www.jcodecraeer.com/uploads/151022/1-1510220ZQQ25.gif)

 

 ## 下拉上拉刷新
 - [BGARefreshLayout-Android多种下拉刷新效果(支持上拉刷新)](https://github.com/bingoogolapple/BGARefreshLayout-Android)
![](https://camo.githubusercontent.com/f609f7944250a6607e5fdec8b12b3156df569cd7/687474703a2f2f37786b39646a2e636f6d312e7a302e676c622e636c6f7564646e2e636f6d2f726566726573686c61796f75742f73637265656e73686f74732f726566726573686c61796f7574312e676966)
- [UltimateRecyclerView](https://github.com/cymcsg/UltimateRecyclerView)
支持ListView、RecycleView上拉刷新以及右滑动删除，支持拖动，动画，和和粘性头部。隐藏和显示Actionbar和ToolBar等
![](https://camo.githubusercontent.com/34707aab637bd5766d183e4bf739e07a589d5aa9/68747470733a2f2f627974656275636b65742e6f72672f6d61727368616c6368656e2f696d616765732f7261772f343462656231363231323163373139656134303934626437656131633966306364376465346330342f756c74696d61746572656379636c6572766965772f756c74696d6174655f72656379636c65727669657731322e676966)
- [Ultra-Pull-To-Refresh](https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh)
此库是单纯的下拉刷新的组件,使用起来简单，`API LEVEL >= 8`可以ui样式十分的简单。还有md风格的下拉刷新样式哦。
![](https://camo.githubusercontent.com/4dfccd5a50f7d59b512300fce341a1217950603a/687474703a2f2f737261696e2d6769746875622e71696e6975646e2e636f6d2f756c7472612d7074722f6d6174657269616c2d7374796c652e676966)

 ## MD
 - [MD风格的dialog](https://github.com/drakeet/MaterialDialog)
 - [Md风格组件的集合](https://github.com/rey5137/material)
 - [RippleView](https://github.com/siriscac/RippleView)
 兼容低版本的水波纹控件
![](https://camo.githubusercontent.com/eec41193900aad4803dcf18bc9915fafa3f7d1cf/68747470733a2f2f7261772e6769746875622e636f6d2f73697269736361632f526970706c65566965772f6d61737465722f53637265656e732f53637265656e2e676966)
 - [MaterialFilePicker](https://github.com/nbsp-team/MaterialFilePicker)
 MD风格的文件选择器

 ## 效果实现
 - [SlidingCard相册的效果](https://github.com/mxn21/SlidingCard) 
![](https://raw.githubusercontent.com/mxn21/SlidingCard/master/screen.gif)
 - [雷达扫描的效果](https://github.com/gpfduoduo/RadarScanView) 
![](https://raw.githubusercontent.com/gpfduoduo/RadarScanView/master/RadarScanView/gif/radar.gif)


  
  
 # 多媒体
 
- [AndroidFFmpeg](https://github.com/appunite/AndroidFFmpeg)
  Android FFmpeg.用于复杂视频处理(转码、压缩、录制视频等)
- [MagicCamera](https://github.com/wuhaoyu1990/MagicCamera)
 集成了美颜滤镜效果。
 ![](https://raw.githubusercontent.com/wuhaoyu1990/MagicCamera/master/Screenshot_1.png)

  
  
  

 # 动画
 
 - [SwitchLayout 视图切换动画](https://github.com/jaychou2012/SwitchLayout)
 - [NiftyDialogEffects 支持自定义飞入动画样式的 Dialog](https://github.com/sd6352051/NiftyDialogEffects)
![](https://camo.githubusercontent.com/456687ac516bb07f1076928d635bfddf6b90d5ec/687474703a2f2f696d67302e70682e3132362e6e65742f69433436653162586b55316631724966555a6f3939773d3d2f363539373632303632313938343031393430382e676966)
- [AndroidViewAnimations](https://github.com/daimajia/AndroidViewAnimations)
View动画的Android库


 # 图像处理
 
- [ImageBlurring图像模糊](https://github.com/qiujuer/ImageBlurring)
- [BitmapMerger图片合成](https://github.com/cooltechworks/BitmapMerger)
![](https://cloud.githubusercontent.com/assets/13122232/8438305/9f7c2644-1f82-11e5-8f51-25ba7cca0711.gif)

 # 功能应用
 
- [pinyin4j的使用(汉字转拼音)](http://wister.iteye.com/blog/334562)
- [MutiPhotoChoser](https://git.oschina.net/xiao-lifan/MutiPhotoChoser)
  自定义相册多图选择  
- [Colorful](https://github.com/bboyfeiyu/Colorful)
  实现了换肤的功能。
  ![](https://raw.githubusercontent.com/hehonghui/Colorful/master/images/colorful.gif)
- [Apk统计自身被卸载](https://github.com/sevenler/Uninstall_Statics)
- [Emoji表情的实现](https://github.com/kymjs/EmojiChat)
 ![](https://raw.githubusercontent.com/kymjs/EmojiChat/master/screen_shots/Screenshot_2.png)

 ## 图表
 [WilliamChart](https://github.com/diogobernardino/WilliamChart)
  
 # Demo
 - [9GAG(整合一些轮子的案例)](https://github.com/stormzhang/9GAG)

