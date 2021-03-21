# HowOldAreYou-
rulerSelectView

UI 
iphone



![Simulator Screen Shot - iPad Pro (12 9-inch) (4th generation) - 2021-03-21 at 17 13 51](https://user-images.githubusercontent.com/15857889/111899634-e0579480-8a68-11eb-9763-b5071ffe4175.png)

ipad
![Simulator Screen Shot - iPad Pro (12 9-inch) (4th generation) - 2021-03-21 at 17 13 51](https://user-images.githubusercontent.com/15857889/111899640-ee0d1a00-8a68-11eb-8496-76cc5bc300ce.png)


### 简单的年龄滚动选择器

使用UICollectionView制作的选择器
添加了滚动响应,使用真机体验滚动效果会更加舒适


### 使用第三方
SnapKit : 布局UI 还是使用它比较舒适

### UnitTest

简单的UnitTest,用于保证数据不会异常
```
 //MARK - 单元测试
    func vulueTest() {
         let vc = ViewController.init()
         vc.rulerSelectValue(value: 10.0, tag: 0)

        XCTAssert(vc.year != "10","结果出错")
    }
```





