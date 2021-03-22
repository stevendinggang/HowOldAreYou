# HowOldAreYou-
rulerSelectView

UI 
iphone

![Simulator Screen Shot - iPhone 12 mini - 2021-03-21 at 18 39 51](https://user-images.githubusercontent.com/15857889/111930921-0165c700-8af5-11eb-8d8e-9eba6c50eec9.png)


ipad
![Simulator Screen Shot - iPad Pro (12 9-inch) (4th generation) - 2021-03-21 at 18 39 34](https://user-images.githubusercontent.com/15857889/111930943-0d518900-8af5-11eb-963e-9f66c34e81e2.png)


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





