[English Docs](./README.md) | [中文文档](./README-zh.md)

# 鸿蒙三方库汇总
持续推荐的鸿蒙三方库，方便开发者学习和使用，排名不分先后。请帮忙Star给与支持 \^_\^。

# 如何使用
如果应用开发时，需要使用某些成熟特性，直接在本文找找吧：
- 使用“command + F”来搜索关键字
- 根据目录分类查找

# 目录
- [JS/ArkTs库](#jsarkts库)
    - [网络](#网络)
    - [图片加载](#图片加载)
    - [动画](#动画)
    - [UI](#UI)
    - [图表](#图表)
    - [媒体](#媒体)
    - [数据存储](#数据存储)
    - [实用工具](#实用工具)
    - [数据序列化和反序列化](#数据序列化和反序列化)
    - [日志](#日志)
    - [安全](#安全)
    - [支付](#支付)
    - [地图](#地图)
    - [其它](#其它)
- C/C++库
- ReactNative三方库
- Flutter三方库 


# 三方库
## JS/ArkTs库
这些库大都已发布在[OpenHarmony三方库中心仓](https://ohpm.openharmony.cn)，使用ohpm install命令安装后，通过ArkTs语言调用。
#### 网络
- [@ohos/axios](https://gitee.com/openharmony-sig/ohos_axios) - 基于[axios](https://github.com/axios/axios)适配鸿蒙Network Kit，并沿用其现有用法和特性，包括拦截器，默认设置，代理，自定义证书等功能。
- [@ohos/mqtt](https://gitee.com/openharmony-tpc/ohos_mqtt) - 基于MQTT协议，发布消息、订阅主题和接收发布的消息。
- [@ohos/httpclient](https://gitee.com/openharmony-tpc/httpclient) - 参考[OkHttp](https://github.com/square/okhttp)设计的一个artts网络库。
- [@ohos/polka](https://gitee.com/openharmony-tpc/openharmony_tpc_samples/tree/master/ohos_polka) - 基于[polka](https://github.com/lukeed/polka)适配，提供了原生的HTTP服务器功能之外，增加了对路由、中间件和子应用程序的支持。

#### 图片加载
- [@ohos/imageknife](https://gitee.com/openharmony-tpc/ImageKnife) - 一个网络图片加载库，提供内存和文件缓存功，预加载，图形变化，自定义网络下载等功能。


#### 动画
- [@ohos/lottie](https://gitee.com/openharmony-tpc/lottieArkTS) - 一个解析Lottie格式的动画，并以原生方式进行渲染的开源库。Lottie动画通常使用Adobe After Effects制作，并通过Bodymovin插件导出为JSON格式。
- [@tencent/libpag](https://github.com/Tencent/libpag) - 一个基于PAG（可移植动画图形）文件的实时渲染库，它可以在大多数平台（如 iOS、安卓、鸿蒙、macOS、Windows、Linux 和 Web）上渲染基于矢量和基于位图的动画。
- [@ohos/gif-drawable](https://gitee.com/openharmony-sig/ohos_gif-drawable) -Gif播放库，支持控制，重置，调整播放速率，监听回调，设置背景色，设置缩放类型等功能。
#### UI
- [@ohos/pulltorefresh](https://gitee.com/openharmony-sig/ohos_pull_to_refresh) - PullToRefresh是一款OpenHarmony环境下可用的下拉刷新、上拉加载组件。 支持设置内置动画的各种属性，支持设置自定义动画，支持lazyForEarch的数据作为数据源。
- [@abner/refresh](https://github.com/AbnerMing888/HarmonyOsRefresh) - 一款简单，高效的上拉下拉刷新组件，支持列表、网格、瀑布流、支持各种任意组件刷新，支持侧滑删除、条目吸顶，下滑二楼等功能。
- [cjcalendar](https://atomgit.com/cj-open/CJOpenNext/tree/master/cjcalendar) - 一款日常开发常用的日历组件，内部集成常规、单选、时间范围选择、多选、自定义日期每项显示等。
- [@ohasasugar/hp-richtext](https://github.com/asasugar/HPRichText) - 一个适用于富文本解析库。
- [@ibestservices/ibest-ui](https://github.com/ibestservices/ibest-ui) - 一个轻量、简单易用、可定制主题、支持深色模式和浅色模式的鸿蒙开源UI组件库。
- [ohos_smart_dialog](https://github.com/xdd666t/ohos_smart_dialog) - 一个参考[flutter_smart_dialog](https://github.com/fluttercandies/flutter_smart_dialog)API设计的Dialog弹窗。
#### 图表
- [@ohos/mpchart](https://gitee.com/openharmony-tpc/ohos_mpchart) - 参考[MPAndroidChart](https://github.com/PhilJay/MPAndroidChart),提供线形图、柱状图、饼状图、蜡烛图、气泡图、雷达图、瀑布图等常用图表库能力。
- [@mcui/mccharts](https://gitee.com/cyaofeng_admin/mc-charts) - (莓创图表)是McUI提供的一款开箱即用的图表工具库。支持折线图、柱状图、饼图、散点图、雷达图等等。
- [@visactor/harmony-vchart](https://www.visactor.io/vchart) - 可视化系统中的图表组件库。它基于可视化语法库 VGrammar 和基于可视化渲染引擎 VRender 的组件封装，封装了基于可视化语法库的图表逻辑。

#### 媒体
- [@ohos/ijkplayer](https://gitee.com/openharmony-sig/ohos_ijkplayer) - 基于[bilibili/ijkplayer](https://github.com/bilibili/ijkplayer)适配鸿蒙操作系统的视频播放器。
- [@ohos/video-cache](https://gitee.com/openharmony-tpc/openharmony_tpc_samples/tree/master/OhosVideoCache) - 一个支持边播放边缓存的库，只需要将音视频的url传递给OhosVideoCache处理之后再设置给播放器，OhosVideoCache就可以一边下载音视频数据并保存在本地，一遍读取本地缓存返回给播放器，使用者无需进行其他操作。
- [@ohos/mp4parser](https://gitee.com/openharmony-tpc/mp4parser) - 一个读取、写入操作音视频文件编辑的库。
#### 数据存储
- [@ohos/dataorm](https://gitee.com/openharmony-sig/ohos_dataorm) -  dataORM 是一个轻量级 ORM（对象关系映射）库，用于简化本地数据库的操作。提供了高效的数据库访问性能和低内存消耗。dataORM 支持多线程操作、链式调用、备份、升级、缓存等特性等功能。
- [@tencent/mmkv](https://github.com/Tencent/mmkv) -  MMKV是基于mmap内存映射的key-value开源库，底层序列化/反序列化使用protobuf实现，性能高且稳定性强。可在Android/macOS/Windows/OpenHarmony等平台使用。
#### 实用工具
- [@yunkss/eftool](https://gitee.com/yunkss/ef-tool) - 借鉴Java的工具类Hutool，提供实用工具涵盖了字符串、数字、集合、JSON等一系列操作。
- [@pura/harmony-utils](https://gitee.com/tongyuyan/harmony-utils) - 一款功能丰富的S工具库，包含APP、设备、屏幕、授权、通知、线程间通信、弹框、吐司、生物认证、用户首选项、拍照、相册、扫码、文件、日志，异常捕获、字符、字符串、数字、集合、日期、随机、base64、加密、解密、JSON等一系列的功能。
- [@peakmain/library](https://gitee.com/peakmain/basic-library) - 一些常用的UI组件和一些实用工具类封装，如导航栏，日历，图片上传，弹窗，时间日期工具，加解密工具，方法注解等功能。
- [@ohos/pinyin4js](https://gitee.com/openharmony-tpc/pinyin4js) - 汉字转拼音。
- [lodash](https://github.com/lodash/lodash) - js原生库可直接用于鸿蒙：提供了一系列有用的功能，用于处理数组、字符串、对象和数字等数据类型。
- [dayjs](https://github.com/iamkun/dayjs) - js原生库可直接用于鸿蒙：用于处理时间和日期。
- [bignumber.js](https://github.com/MikeMcl/bignumber.js) - js原生库可直接用于鸿蒙：支持任意精度的小数和非小数的运算。
- [json-bigint](github.com/sidorares/json-bigint) - js原生库可直接用于鸿蒙：JSON.parse/stringify支持超大整数。
- [reflect-metadata](https://github.com/rbuckton/reflect-metadata) - js原生库可直接用于鸿蒙：在运行时获取和操作JavaScript对象和类的装饰器上的元数据。
- [validator](https://github.com/validatorjs/validator.js) - js原生库可直接用于鸿蒙：验证并清理字符串。


#### 数据序列化和反序列化
- [@ohos/protobufjs](https://gitee.com/openharmony-tpc/protobuf) - 基于[protobufjs](https://github.com/protobufjs/protobuf.js)适配，提供一种语言无关、平台无关、可扩展的序列化结构数据的方法，它可用于（数据）通信协议、数据存储等。
- [pako](github.com/nodeca/pako) - js原生库可直接用于鸿蒙：处理gzip压缩和解压数据。
#### 日志
- [@pie/log4a](https://gitcode.com/OneSoft/log4a) - 轻量、易集成、易使用的日志库。
#### 安全
- [@ohos/crypto-js](https://gitee.com/openharmony-sig/ohos_crypto_js) - 支持MD5、SHA-1、SHA-256、HMAC、HMAC-MD5、HMAC-SHA1、HMAC-SHA256、PBKDF2、AES、RC4、DES等。
#### 支付
- [@cashier_alipay/cashiersdk](https://ohpm.openharmony.cn/#/cn/detail/@cashier_alipay%2Fcashiersdk) -  支付宝支付SDK。
- [@tencent/wechat_open_sdk](https://ohpm.openharmony.cn/#/cn/detail/@tencent%2Fwechat_open_sdk) - 微信开放平台SDK，让你的移动应用支持微信分享、微信收藏和微信支付。
#### 地图
- [@amap/amap_lbs_map3d](https://ohpm.openharmony.cn/#/cn/detail/@amap%2Famap_lbs_map3d) -  高德地图 地图SDK。
- [@amap/amap_lbs_location](https://ohpm.openharmony.cn/#/cn/detail/@amap%2Famap_lbs_location) - 高德地图 定位SDK。
- [@bdmap/map](https://ohpm.openharmony.cn/#/cn/detail/@bdmap%2Fmap) - 百度地图和定位SDK。
- [@tencentmap/map](https://ohpm.openharmony.cn/#/cn/detail/@tencentmap%2Fmap) - 腾讯地图和定位SDK。
#### 其它
- [@ohos/aki](https://gitee.com/openharmony-sig/aki) - 一款边界性编程体验友好的ArkTs FFI开发框架，针对OpenHarmony Native开发提供JS与C/C++跨语言访问场景解决方案。支持极简语法糖使用方式，一行代码完成JS与C/C++的无障碍跨语言互调，所见即所得。
- [@coremail/mail_base](https://gitee.com/openharmony-tpc/ohos_mail_base) - 邮件SDK：方便开发邮件客户端而开发。提供了标准邮件协议解析，MIME格式解析，MSG格式解析等邮件客户端相关的功能。
- [@luvi/lv-markdown-in](https://gitee.com/luvi/lv-markdown-in) - Markdown解析预览库。
- [@ohos/zxing](https://gitee.com/openharmony-tpc/zxing) - 一个解析/生成一维码/二维码的库。

## C/C++库
C/C++库多需要源码引入，这里只提供了在鸿蒙下交叉编译的方法。

## ReactNative三方库 

## Flutter三方库 

# 一起维护
如果有更强大更好用的库，欢迎提issue给我。

# 联系我
- 微信公众号：还没做。。
- B站：还没做。。
- 小红书：还没做。。