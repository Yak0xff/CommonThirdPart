# CommonThirdPart
项目中常用的第三方库整理


> 本三方库整理均为Objetive-C版


iOS开发中难免使用到一些第三方的类库，以减少工作量，将重点放在软件本身的逻辑实现上。

GitHub里面有大量优秀的第三方框架，而且License对商业很友好。一下摘录一下几乎每个项目都想集成的几个框架。


##### 1. Mantle


> Mantle让我们能简化Cocoa和Cocoa Touch应用的model层。简单点说，程序中经常要进行网络请求，请求到得一般是json字符串，我们一般会建一个Model类来存放这些数据。这就要求我们编写一系列的序列化代码，来把json转换为Model。这很费时间，容易错，不容易修改。Mantle很好的解决了这个问题，而且更易用。


* GitHub ： [https://github.com/Mantle/Mantle](https://github.com/Mantle/Mantle)
* CocoaPod集成：```pod 'Mantle'```


##### 2. Masonry

> IB时代，如果你还在用代码绝对布局就太low了。随着苹果发布iPhone6、iPhone 6 plus。iOS设备将会出现越来越丰富的屏幕尺寸，我们不可能根据每个尺寸做一套布局。所以，使用autolayout就很有必要了。在storyboard中，可以非常方便的使用autolayout，但是为了更好的协作开发，有些公司依然在手写布局，令人沮丧的是苹果提供的autolayout语法晦涩难懂，非常影响效率（你可以在这里动态查看autolayout的语法）。Masonry就是设计来解决复杂的手写autolayout。如何优雅的使用autolayout，且看Masonry。


* GitHub ： [https://github.com/Masonry/Masonry](https://github.com/Masonry/Masonry)
* CocoaPod集成：```pod 'Masonry'```


##### 3. BlocksKit


> BlocksKit绝对是Objective-C的知心伴侣，它为OC常用类提供了强大的Block语法支持，使得编写OC代码变得舒适、快速、优雅。反正我是绝对离不开它。


* GitHub ： [https://github.com/zwaldowski/BlocksKit](https://github.com/zwaldowski/BlocksKit)
* CocoaPod集成：```pod 'BlocksKit'```


##### 4. KVOController


> 如果你在项目中有使用KVO，那么KVOController绝对是个好选择。它是facebook开源的一个KVO增强框架。有以下几个特性：

> 使用 Blocks、自定义 Actions 或者 NSKeyValueObserving 回调进行通知.
观测者移除时无异常
控制器 dealloc 时隐式的观测者移除
提升使用 NSKeyValueObservingInitial 的性能
线程安全并提供在观测者恢复时额外的保护
还有什么理由不使用KVOController呢？

* GitHub ： [https://github.com/facebook/KVOController](https://github.com/facebook/KVOController)
* CocoaPod集成：```pod 'KVOController'```


##### 5. MBProgressHUD


> 一个老牌、经典的通知组件，如果你们美工没有专门设计等待和通知视图，那就用它吧！


* GitHub ： [https://github.com/jdg/MBProgressHUD](https://github.com/jdg/MBProgressHUD)
* CocoaPod集成：```pod 'KVOController'```


##### 6. AFNetworking


> Objective-C下网络请求库。

* GitHub ： [https://github.com/AFNetworking/AFNetworking](https://github.com/AFNetworking/AFNetworking)
* CocoaPod集成：```pod 'AFNetworking'```


##### 7. SDWebImage

> 帮助你异步加载网络图片，当然，它有缓存功能。简单、实用、功能强大。

* GitHub ： [https://github.com/rs/SDWebImage](https://github.com/rs/SDWebImage)
* CocoaPod集成：```pod 'SDWebImage'```


##### 8. TTTAttributedLabel

> TTTAttributedLabel 是功能强大的UILabel，包含大部分对UILabel的定制。如果你想让一个UILabel可以点击并截取它，那么使用TTTAttributedLabel吧

* GitHub ： [https://github.com/TTTAttributedLabel/TTTAttributedLabel](https://github.com/TTTAttributedLabel/TTTAttributedLabel)
* CocoaPod集成：```pod 'TTTAttributedLabel'```