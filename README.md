[English Docs](./README.md) | [中文文档](./README-zh.md)

# Awesome Harmony Library[![Awesome](https://awesome.re/badge.svg)](https://github.com/Madixin/awesome-harmony-library)
A curated list of awesome library for OpenHarmony/HarmonyOS.The ranking is not in order.
Your star would make me keep updated. Thank you.

# How to use
It is an amazing list for people who need a certain feature on their app,so the best ways to use are:
- Simply press command + F to search for a keyword
- Go through our Content Menu

# Content
- [JS/ArkTs Library](#jsarkts-library)
    - [Networking](#networking)
    - [Images](#images)
    - [Animations](#animations)
    - [UI](#ui)
    - [Charts](#charts)
    - [Media](#media)
    - [Data storage](#data-storage)
    - [Utility](#utility)
    - [Serialization/Deserialization](#serializationdeserialization)
    - [Payment](#payment) 
    - [Logger](#logger)
    - [Security](#security)
    - [Map](#map)
    - [Others](#others)
- C/C++ Library
- ReactNative Library
- Flutter Library 

# Librarys
## JS/ArkTs Library
Most of these libraries have been published in [OpenHarmony Third-Party Library Repository](https://ohpm.openharmony.cn). After installing them using the "ohpm install" command, you can import and use them through the ArkTs language.
#### Networking
- [@ohos/axios](https://gitcode.com/openharmony-sig/ohos_axios) - Adapt the OpenHarmony Network Kit based on[axios](https://github.com/axios/axios), while maintaining its existing usage and features, including interceptors, default settings, proxies, custom certificates, and other functionalities.
- [@ohos/mqtt](https://gitcode.com/openharmony-tpc/ohos_mqtt) - Based on the MQTT protocol, publish messages, subscribe to topics, and receive published messages.
- [@ohos/httpclient](https://gitcode.com/openharmony-tpc/httpclient) - A network library for ARTTS designed with reference to [OkHttp](https://github.com/square/okhttp).
- [@ohos/polka](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/tree/master/ohos_polka) - Base on [polka](https://github.com/lukeed/polka), provide native HTTP server functionality, it adds support for routing, middleware, and sub-applications.
#### Images
- [@ohos/imageknife](https://gitcode.com/openharmony-tpc/ImageKnife) - A network image loading library that provides functionality for memory and file caching, preloading, image transformation, custom network downloads, and more.
#### Animations
- [@ohos/lottie](https://gitcode.com/openharmony-tpc/lottieArkTS) - An open-source library that parses animations in the Lottie format and renders them natively. Lottie animations are typically created using Adobe After Effects and exported as JSON files via the Bodymovin plugin.
- [@tencent/libpag](https://github.com/Tencent/libpag) - A real-time rendering library for PAG (Portable Animated Graphics) files that renders both vector-based and raster-based animations across most platforms, such as iOS, Android, OpenHarmony, macOS, Windows, Linux, and Web.
- [@ohos/gif-drawable](https://gitcode.com/openharmony-sig/ohos_gif-drawable) - A library for rendering gif.Support control,reset,set speed,listen callback, set backgroud,set scale type and so on.
- [@ohos/apng](https://gitcode.com/openharmony-sig/ohos_apng) - Display and Control apng Animations.
#### UI
- [@ohos/pulltorefresh](https://gitcode.com/openharmony-sig/ohos_pull_to_refresh) - PullToRefresh is an OpenHarmony UI component which allows users to pull down on a list or a page to trigger a refresh action and pull up to trigger a load action. You can set built-in animation properties, customize animations, and use lazyForEarch data as the data source.
- [@abner/refresh](https://github.com/AbnerMing888/HarmonyOsRefresh) - It's a simple and efficient pull-to-refresh and drag-down-to-refresh component that supports lists, grids, and waterfall flows. It allows for refreshing various arbitrary components and features side swipe deletion, sticky headers, and swipe-down-to-access-second-level-menu functionalities.
- [cjcalendar](https://atomgit.com/cj-open/CJOpenNext/tree/master/cjcalendar) - A calendar library commonly used in daily development, internally integrated with functions such as regular selection, single selection, time range selection, multiple selection, and custom display for each date item.
- [@ohasasugar/hp-richtext](https://github.com/asasugar/HPRichText) - A library for rich text parsing.
- [@ibestservices/ibest-ui](https://github.com/ibestservices/ibest-ui) - A lightweight, easy-to-use, theme-customizable open-source UI component library that supports both dark and light modes.
- [ohos_smart_dialog](https://github.com/xdd666t/ohos_smart_dialog) - A Dialog pop - up designed with reference to the API of[flutter_smart_dialog](https://github.com/fluttercandies/flutter_smart_dialog).

#### Charts
- [@ohos/mpchart](https://gitcode.com/openharmony-tpc/ohos_mpchart) - Refer to[MPAndroidChart](https://github.com/PhilJay/MPAndroidChart), it provides common chart library capabilities such as line charts, bar charts, pie charts, candlestick charts, bubble charts, radar charts, waterfall charts, and more.
- [@mcui/mccharts](https://gitee.com/cyaofeng_admin/mc-charts) - A library for charts,supports line charts, bar charts, pie charts, scatter plots, radar charts, and more.
- [@visactor/harmony-vchart](https://www.visactor.io/vchart) - A library for charts,it encapsulates chart logic based on the visualization grammar library VGrammar and components based on the visualization rendering engine VRender.
#### Media
- [@ohos/ijkplayer](https://gitcode.com/openharmony-sig/ohos_ijkplayer) - A video player adapted to the HarmonyOS/OpenHarmony based on[bilibili/ijkplayer](https://github.com/bilibili/ijkplayer).
- [@ohos/video-cache](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/tree/master/OhosVideoCache) - A library that supports caching during playback. You only need to pass the URL of the media to OhosVideoCache for processing and then set it to the player. 
- [@ohos/mp4parser](https://gitcode.com/openharmony-tpc/mp4parser) - A library for reading and writing audio and video files.
- [@rte-xhs/redplayer](https://github.com/RTE-Dev/REDPlayer) - is a cross-platform (supporting Android, iOS, HarmonyOS, and other platforms) player independently developed by Xiaohongshu. Different from other players in the industry, REDPlayer has the characteristics of simple structure, low coupling, and clear functional boundary. It provides a variety of access methods, and technicians can choose flexibly according to needs. They can quickly integrate SDK for use, or customize development based on source code.

#### Data storage
- [@ohos/dataorm](https://gitcode.com/openharmony-sig/ohos_dataorm) -  A lightweight object relational mapping (ORM) library used to simplify operations on local databases, offering efficient database access performance and low memory consumption. dataORM supports multi-threading, chain calling, backup, upgrade, and caching. Designed for speed and simplicity, it helps you quickly build high-performance applications.
- [rdbstore](https://github.com/bytedance/rdbStore) -  provided by ByteDance is provided to developers in the form of relationalStore related interfaces. RDbStore performs database operations in the form of DTO objects, encapsulates database creation and automatic upgrade, database predicate construction, query result deserialization, quality tuning and other capabilities, and realizes simple and efficient database operations.
- [@tencent/mmkv](https://github.com/Tencent/mmkv) -  MMKV is an open-source key-value library based on mmap memory mapping. It uses protobuf for underlying serialization/deserialization, providing high performance and strong stability. It can be used on platforms such as Android, macOS, Windows, and OpenHarmony.
#### Utility
- [@yunkss/eftool](https://gitee.com/yunkss/ef-tool) - Inspired by Java's utility class Hutool, this provides a suite of practical tools covering a wide range of operations including strings, numbers, collections, JSON, and more.
- [@pura/harmony-utils](https://gitee.com/tongyuyan/harmony-utils) - A util library, including APP, device, screen, authorization, notification, inter-thread communication, pop-up, toast, biometric authentication, user preferences, photo taking, photo album, code scanning, file, log, exception capture, character, string, number, collection, date, random, base64, encryption, decryption, JSON and a series of other functions.
- [@peakmain/library](https://gitee.com/peakmain/basic-library) - Some commonly used UI components and some utility class encapsulations, such as navigation bars, calendars, image uploads, pop-ups, time and date tools, encryption and decryption tools, method annotations, and other functions.
- [@ohos/pinyin4js](https://gitcode.com/openharmony-tpc/pinyin4js) - A library for Convert Chinese Characters to Pinyin.
- [lodash](https://github.com/lodash/lodash) - Native JavaScript libraries can be directly used in OpenHarmony for provides a series of useful functions for handling data types such as arrays, strings, objects, and numbers.
- [dayjs](https://github.com/iamkun/dayjs) - Native JavaScript libraries can be directly used in OpenHarmony for handling time and dates.
- [bignumber.js](https://github.com/MikeMcl/bignumber.js) - Native JavaScript libraries can be directly used in OpenHarmony for arbitary-precision decimal and non-decimal arithmetic.
- [json-bigint](github.com/sidorares/json-bigint) - Native JavaScript libraries can be directly used in OpenHarmony for JSON.parse/stringify with bigints support. 
- [reflect-metadata](https://github.com/rbuckton/reflect-metadata) - Native JavaScript libraries used for get metadata on decorators for JavaScript objects and classes.
- [validator](https://github.com/validatorjs/validator.js) - Native JavaScript libraries used for This library validates and sanitizes strings.

#### Serialization/Deserialization
- [@ohos/protobufjs](https://gitcode.com/openharmony-tpc/protobuf) - Base on[protobufjs](https://github.com/protobufjs/protobuf.js)，provide a language-neutral,platfrom-neutral,extensible way of serializing structured data for use in communications protocols,data storage,and more.
- [pako](github.com/nodeca/pako) - Native JavaScript libraries used for gzip and ungzip data.
#### Logger
- [@pie/log4a](https://gitcode.com/OneSoft/log4a) - A lightweight, easy-to-integrate, and easy-to-use logging library.
#### Security
- [@ohos/crypto-js](https://gitcode.com/openharmony-sig/ohos_crypto_js) - Support MD5、SHA-1、SHA-256、HMAC、HMAC-MD5、HMAC-SHA1、HMAC-SHA256、PBKDF2、AES、RC4、DES and so on.
#### Payment 
- [@cashier_alipay/cashiersdk](https://ohpm.openharmony.cn/#/cn/detail/@cashier_alipay%2Fcashiersdk) -  Alipay SDK.
- [@tencent/wechat_open_sdk](https://ohpm.openharmony.cn/#/cn/detail/@tencent%2Fwechat_open_sdk) - Wechat open sdk.
#### Map
- [@amap/amap_lbs_map3d](https://ohpm.openharmony.cn/#/cn/detail/@amap%2Famap_lbs_map3d) -  Amap Map SDK.
- [@amap/amap_lbs_location](https://ohpm.openharmony.cn/#/cn/detail/@amap%2Famap_lbs_location) - Amap Locate SDK.
- [@bdmap/map](https://ohpm.openharmony.cn/#/cn/detail/@bdmap%2Fmap) - bdmap map and locate SDK.
- [@tencentmap/map](https://ohpm.openharmony.cn/#/cn/detail/@tencentmap%2Fmap) - tencent map and locate SDK.
#### Others
- [@ohos/aki](https://gitcode.com/openharmony-sig/aki) - Alpha Kernel Interacting (AKI) is a user-friendly development framework that allows interactions between JavaScript (JS) and C/C++ in OpenHarmony native development. It provides seamless calls between C/C++ and JS, using simplified syntactic sugar.
- [@bytedance/byte_global_viewpool](https://github.com/bytedance/bGlobalViewPool) - provided by ByteDance solves common problems in cross end component development, such as page sliding and frame loss, main thread blocking, poor smoothness of long lists, etc., through cross end component pre creation capability, reuse pool automatic pool filling sub capability, OnIdle pre creation and other capabilities, and is especially suitable for frequent page switching scenarios such as news lists and shopping pages.
- [@coremail/mail_base](https://gitcode.com/openharmony-tpc/ohos_mail_base) - Email SDK: Developed to facilitate the creation of email clients. It provides functionalities pertinent to email clients such as parsing of standard email protocols, MIME format parsing, MSG format parsing, and more.
- [@luvi/lv-markdown-in](https://gitee.com/luvi/lv-markdown-in) - A library for Markdown parsing and preview.
- [@ohos/zxing](https://gitcode.com/openharmony-tpc/zxing) - A library for parsing/generating one-dimensional codes/two-dimensional codes.

## C/C++ Library
Most C/C++ libraries require source code integration. Here, only provided the method of cross - compilation in OpenHarmony.
## ReactNative Library

## Flutter Library 

# Contributing
If there are more easy-use and powerful libraries, feel free to submit an issue to me.

# Contact me