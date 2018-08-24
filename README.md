# V1.1 #

# 先上个效果图 #

![效果图](https://github.com/manitozhang/StatusBar/tree/master/statusbar/src/main/res/drawable.show.png)


这是一个可以改变状态栏颜色以及使状态栏变透明的依赖库

## 使用方法: ##

添加  

         maven { url 'https://jitpack.io' } 
        
        
到你的工程下的build.gradle ---> allprojects ---> repositories 的标签下


添加

      implementation 'com.github.manitozhang:StatusBar:1.0'

到你的 moudle 下的 dependencies 标签下

配置就已经完成了

## 调用方法: ##

      ### 设置状态栏为固定颜色 ###
      Eyes.setStatusBarLightMode(Activity activity, int Color); 
      
      
      ### 设置状态栏为透明 ###
      Eyes.translucentStatusBar(Activity activity, boolean hideStatusBarBackground);
      
      
 # 后续会持续进行更新 #
        
        
