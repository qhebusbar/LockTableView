# LockTableView
对LockTableView进行AndroidX适配

详细使用说明请看:https://github.com/RmondJone/LockTableView

## 工程集成说明
* 第一步
```java
//在工程gradle文件里
allprojects {
    repositories {
        .......
        maven { url 'https://jitpack.io' }
        ......
    }
}
```

* 第二步 tag:[![](https://www.jitpack.io/v/Nick5290/LockTableView.svg)](https://www.jitpack.io/#Nick5290/LockTableView)
```java
dependencies {
	implementation 'androidx.appcompat:appcompat:1.2.0'
	implementation 'androidx.recyclerview:recyclerview:1.2.0'
	implementation 'com.google.android.material:material:1.2.0'
	
	implementation 'com.github.RmondJone:LockTableView:tag'
}
```
