# LeakcanarySample-Eclipse Dparted

本项目是根据[Leakcanary](https://github.com/teffy/leakcanary)项目(version 1.3.1)改造而来的，本人项目中用到Leakcanary，如果只是作为普通app来开发，只需要根据leakcanary项目说明中的一样，添加
```
dependencies {
   debugCompile 'com.squareup.leakcanary:leakcanary-android:1.3.1'
   releaseCompile 'com.squareup.leakcanary:leakcanary-android-no-op:1.3.1'
 }
```
即可；

但是本人做rom开发，项目要编进rom中，所以需要通过源码来编译，需要把code放进项目中，所以就根据Leakcanary改造成了一个Eclipse项目，方便拿到code，也方便如果有依然坚持使用Eclipse来开发项目的同学们。
使用方法就是使用Eclipse进行项目依赖就可以了。
