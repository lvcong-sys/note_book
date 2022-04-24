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
