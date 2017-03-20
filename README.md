# QxIOSDevDocument
苹果开发的好的三方文档收集
包括Object-C和swift

网络连接

1. AFNetworking – ASI不升级以后，最多人用的网络连接开源库，[推荐]iOS网络编程之AFNetworking使用,
iOS开发下载文件速度计算。
2. Alamofire – Alamofire是AFNetworking的作者mattt新写的网络请求的swift库。
3. YTKNetwork – 是基于 AFNetworking 封装的 iOS网络库，提供了更高层次的网络访问抽象。相比AFNetworking，YTKNetwork提供了以下更高级的功能：
      按时间或版本号缓存网络请求内容、检查返回 JSON 内容的合法性、文件的断点续传、批量的网络请求发送、filter和插件机制等。
4. LxFTPRequest – 支持获取FTP服务器资源列表，下载/上传文件，创建/销毁ftp服务器文件/目录，以及下载断点续传，下载/上传进度，
       自动判断地址格式合法性跟踪等功能！国人开发，QQ：349124555。
5. WTRequestCenter – 方便缓存的请求库，提供了方便的HTTP请求方法，传入请求url和参数，返回成功和失败的回调。 UIKit扩展提供了许多不错的方法，
    快速缓存图片，图片查看，缩放功能， 颜色创建，设备UUID，网页缓存，数据缓存等功能。 无需任何import和配置，目前实现了基础需求。
6. MMWormhole – Message passing between iOS apps and extensions 2个iOS设备之间通信。
7. Transporter – swift， 短小、精悍、易用的多文件（并发或顺序）上传和下载传输库。还支持后台运行、传输进程跟踪、暂停/续传/取消/重试控制等功能。
8. STNetTaskQueue – STNetTaskQueue Objective-C 可扩展网络请求管理库。
9. CocoaAsyncSocket – 在iOS开发中使用socket，一般都是用第三方库AsyncSocket，不得不承认这个库确实很强大，使用教程。
10. GCDAsyncSocket – GCDAsyncSocket ， 不错的Demo。
11. Just – 小而美的 HTTP 类。功能简单、直接、完整且健壮性高– swift。
12. Future – 基于微框架设计思想的异步执行及结果响应类，代码即简单又干净– swift。
13. MZDownloadManager – 下载管理。
14. DVR – 针对网络请求的测试框架，超实用的工具。且支持 iOS, OSX, watchOS 全平台。
15. socket.io-client-swift – WebSockect 客户端类库。开放的通讯协议，有利于构建强大地跨平台应用。
16. Reachability ：swift获取系统当前的网络状态和检测应用是否可以连接到后台服务器。
图像获取

1. SDWebImage – SDWebImage 网络图片获取及缓存处理。
2. Kingfisher – 纯 Swift 实现的类 SDWebImage 库，实现了异步下载和缓存图片。
3. KFSwiftImageLoader – Swift，一个图像缓存加载库。
4. FastImageCache – FastImageCache 网络图片获取及缓存处理，iOS图片加载速度极限优化—FastImageCache解析。
5. EGOCache – 十分知名的第三方缓存类库，可以缓存NSString、UIImage、NSImage以及NSData。除此，如果还可以缓存任何一个遵守协议的对象。
   所有缓存的数据都可以自定义过期的时间，默认是1天。EGOCache 支持多线程（thread-safe），UITableView加载多张照片导致内存上涨的问题。
6. AlamofireImage：开发Alamofire网络框架的开发针对swift的图片处理框架
7. GPImage ：https://github.com/BradLarson/GPUImage
    GPUImage是一个基于GPU图像和视频处理的开源iOS框架。主要功能如下：
    提供各种各样的图像处理滤镜，并且支持照相机和摄像机的实时滤镜；
    GPUImage顾名思义，是基于GPU的图像加速，因此图像处理速度非常快，并且能够自定义图像滤镜；
    支持ARC。
 
网络聊天

1. XMPPFramework – XMPPFramework openfire聊天。
2. 环信 – 给开发者更稳定IM云功能。8200万用户考验，好用！（暂无及时语音、视频通话）
3. 融云 – 即时通讯云服务提供商。（暂无及时语音、视频通话）
4. 容联云通讯 – 提供基于互联网通话,视频会议,呼叫中心/IVR,IM等通讯服务。
5. chatsecure – 基于XMPP的iphone、android加密式聊天软件， chatsecure官网 。 iOS代码1，iOS代码2， iOS中文版。
6. MessageDisplayKit – 仿微信聊天，参考JSQMessagesViewController。（国人写）
7. JSQMessagesViewController – 聊天 。
8. SunFlower – 环信聊天demo，比较多功能 。
9. BlueTalk蓝牙聊天 – 以MultipeerConnectivity为基础， 实现了简单的蓝牙聊天。

WebView

1. MGTemplateEngine – MGTemplateEngine比较象 PHP 中的 Smarty、FreeMarker 和 Django的模版引擎，是一个轻量级的引擎，简单好用。
     只要设置很多不同的HMTL模版，就能轻松的实现一个View多种内容格式的显示，对于不熟悉HTML或者减轻 工作量而言，把这些工作让设计分担一下还是很好的，
     也比较容易实现设计想要的效果。
2. NJKWebViewProgress – 一个 UIWebView 的进度条接口库,UIWebView 本身是不提供进度条的。
3. GTMNSString-HTML – 谷歌开源的用于过滤HTML标签。

 
Model

1. YYModel - 高性能 iOS/OSX 模型转换框架。(该项目是 YYKit 组件之一)，据称性能做好的Model和Json互转的三方库。（推荐）
2. JSONKit – JSONKit库是非常简单易用而且效率又比较高的，重要的JSONKit适用于ios 5.0以下的版本,使用JSONKit库来解析json文件，
    只需要下载JSONKit.h 和JSONKit.m添加到工程中；然后加入libz.dylib即可。
3. JSONModel – 解析服务器返回的Json数据的库,JSONModel源码解析一。
4. Mantle – Mantle主要用来将JSON数据模型化为OC对象, 大系统中使用。为什么选择Mantle。
5. RFJModel – RFJModel是一个IOS类库，可以将JSON字典自动装填到OBJC对象。相比JSONModel有一些非常好的特性，使用上也比较简单。
6. XMLDictionary – ios与mac os平台下xml与NSDictionary相互转化开源类库。
7. MJExtension – 用于json转model进行使用，转换效率很高，使用也比较简单，只要前后台约定好，json直接就转成了model。
8. CFRuntime – “Swift 版的 MJExtension，运行时、反射与一键字典模型互转”。
9. DDModel – 快速搭建项目Model层，支持ORM映射关系，能从JSON/XML直接实例一个Model对象。支持SQLite本地数据持久化，封装了HTTP， 减少HTTP代码与UIViewController的代码耦合，支持Cache；类似RESTKit、Mantle的功能；使用该类库以后简化了网络层的开发工作，把更多的精力放在UI上面；目前只支持GET/POST方法的请求。使用到的第三方库有：1.SQLitePersistentObject; 2.JTObjectMapping; 3.AFNetworking; 4.XMLDictionary;
10. protobuf-swift – Protocol Buffers 的 Swift 语言实现库。P.S. Protocol Buffers 是 Google 开源项目，主要功能是实现直接序列化结构化
   的对象数据，方便跨平台快速传递，开发者也可以直接修改 protobuf 中的数据。相比 XML 和 JSON，protobuf 解析更快，存储更小。
11. JSONCodable – 基于 Swift 2.0 新特性（Protocol Extensions and Error Handling）的JSON 解析类。
12. SwiftyJSON类似于YYModle的swift实现的json-object相互转化的工具类

响应式编程

1.RAC：Reactive Cocoa（RAC）是一个支持FRP(函数响应式编程)的框架支持Object-C

2.RxSwift：类似于与RxJava支持swift三方开源框架

others

1.CSSwiftExtension：是一个Swift的extension集合, 包含了一些常见的方法:地址：https://github.com/icetime17/CSSwiftExtension
  如Foundation的一些基本extension方法，以及, UIImage的缩放cs_imageScaledToSize, 以及不会引起离屏渲染的图片圆角cs_imageWithCornerRadius等，
   UIDevice的一些常见方法, 以及UIApplication的cs_currentViewController可用于获取当前的ViewController,
   cs_isRunningAppVersionReleased方法接收当前App在AppStore中的id, 即可查询当前版本是否已经release.
