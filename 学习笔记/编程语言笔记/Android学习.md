# Android学习笔记

## 基础控件学习

* Button

* Toast
  
  > 在kotlin中使用kotlin-android-extensions插件以减少对R.id代码的编写

## 所遇到的bug

* ==Caused by: org.gradle.api.internal.plugins.PluginApplicationException: Failed to apply plugin 'com.android.internal.application'==

  在项目中的gradle.properties文件中添加语句：

  ```kotlin
  android.overridePathCheck=true
  ```

  

## AndroidStudio的使用

* 需求

  > 1. 网络通信
  >
  >    > 通过http来进行用户注册。用户的相关业务有
  >    >
  >    > - [ ] 对视频进行评价(需要对mysql数据库进行操作)
  >    > - [ ] 对视频进行缓存(本地数据库)
  >    > - [ ] 对视频进行收藏(需要对mysql数据库进行操作)
  >    > - [ ] 对视频视频号进行收藏(需要对mysql数据库进行操作)
  >    > - [x] 播放视频
  >    > - [x] 搜索视频
  >    > - [ ] 注册登录(需要对mysql数据库进行操作)
  >    > - [ ] 观看记录(需要对mysql数据库进行操作)
  >
  > 2. 数据库服务器(对照1)
  >
  > 3. 传感器
  >
  >    > - [ ] 播放视频的自动旋转
  >
  > 4. 多线程(有待考究)
  
* MVVM架构

  > * 结构图：
  >
  >   > ![](https://img-blog.csdnimg.cn/20181202205406353.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MDM3MDQ3,size_16,color_FFFFFF,t_70)
