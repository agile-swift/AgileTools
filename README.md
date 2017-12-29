# AgileTools

全生态 Agile Tools 集合，快速 Swift 开发

## 组件

|模块       |功能         |依赖           |
| -------------|:--------------:|:--------------:|:--------------:| ------:|
|ATFoundation|APP开发基本功能集合|-|
|ATUIKit|基本UI功能集合，主要重写Navagation/tabbar/ViewController|-|
|ATRequest|基于Alamofire的网络请求封装| Alamofire/YYCache/HandyJSON|
|ATDebug|开发调试功能集成| ATFoundation/ATUIKit/ATRequest/GDPerformanceView-Swift|
|ATCycleView|高性能无限轮播| ATTimer |
|ATTimer|基于GCD的定时器|-|
|ATRefresh|扩展性强的刷新组件|-|
|ATListView|高效列表开发（上拉/下拉/cell高度自动计算/错误页面/空页面）| ATRefresh |
|。。。|。。。|。。。|

## 集成([CocoaPods](http://cocoapods.org))

在 podfile 文件中添加

```
source "https://github.com/agile-swift/Specs.git"
pod 'AgileTools'
```

以上会集成所有AT组件。或者可以针对部分组件集成使用

```
source "https://github.com/agile-swift/Specs.git"
pod 'ATFoundation'
pod 'ATUIKit'
...
```

## 反馈

devkevinma@gmail.com, admin@makaiwen.com
