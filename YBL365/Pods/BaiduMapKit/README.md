# BaiduMapKit

百度地图 iOS SDK(官方)





--------------------------------------------------------------------------------------

iOS 地图 SDK v3.2.0是适用于iOS系统移动设备的矢量地图开发包

--------------------------------------------------------------------------------------

地图SDK功能介绍（全功能开发包）：

地图：提供地图展示和地图操作功能；

POI检索：支持周边检索、区域检索和城市内兴趣点检索；

地理编码：提供经纬度和地址信息相互转化的功能接口；

线路规划：支持公交、驾车、步行三种方式的线路规划；

覆盖物图层：支持在地图上添加覆盖物（标注、几何图形、热力图、地形图图层等），展示更丰富的LBS信息；

定位：获取当前位置信息，并在地图上展示（支持普通、跟随、罗盘三种模式）；

离线地图：使用离线地图可节省用户流量，提供更好的地图展示效果；

调启百度地图：利用SDK接口，直接在本地打开百度地图客户端或WebApp，实现地图功能；

周边雷达：利用周边雷达功能，开发者可在App内低成本、快速实现查找周边使用相同App的用户位置的功能；

LBS云检索：支持查询存储在LBS云内的自有数据；

特色功能：提供短串分享、Place详情检索、热力图等特色功能，帮助开发者搭建功能更加强大的应用；


--------------------------------------------------------------------------------------


注：自v3.2.0起，百度地图iOS SDK全面支持HTTPS，需要广大开发者导入第三方openssl静态库：libssl.a和libcrypto.a（存放于thirdlib目录下）。


【 新版提示 】

1、自v3.2.0起，全面支持HTTPS

2、自v3.2.0起，地图引擎全面升级，主要升级特征有：

渲染架构技术升级，OpenGL ES从1.0升级到2.0

地图数据加载升级，加载性能大幅提升


【 修  复 】

 修复下载离线地图时，delegate方法返回state错误问题