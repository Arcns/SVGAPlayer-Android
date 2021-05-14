[![](https://www.jitpack.io/v/Arcns/AllAngleExpandableButton.svg)](https://www.jitpack.io/#Arcns/AllAngleExpandableButton)

### 感谢svga！相比[svga/SVGAPlayer-Android](https://github.com/svga/SVGAPlayer-Android) ,根据我的实际需求做了以下修改：
```
//新增开启/禁用动画音效
SVGACanvasDrawerKt.setEnableSVGASound(false)
```

```
allprojects {
	repositories {
		...
		maven { url 'https://www.jitpack.io' }
	}
}
```
	
```
dependencies {
	implementation 'com.github.Arcns:SVGAPlayer-Android:Tag'
}
```

其他使用方法请查阅[svga/SVGAPlayer-Android](https://github.com/svga/SVGAPlayer-Android)
