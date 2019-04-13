## これだけは抑えておくポイント
- 画面サイズを取得してそれを基準にすることで，どのサイズの端末にも対応できる．
```
let screenSize = UIScreen.main.bounds.size
```
- 加速度センサを使うときはCoreMotionライブラリをインポートして，CMMotionManagerを使うことを宣言する．
```
import CoreMotion
~クラス内~
var playerMotionManager: CMMotionManager!
```


## Swiftの言語特性
- switch文の書き方
```
switch 変数名 {
  case 値1:
     処理
  case 値2:
     処理
  case 値3:
     処理
  default:
     処理
}
```

