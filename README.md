# TC 仪表大屏地图投射

#99.0.21 CarPlay ETA数据入口测试版

99.0.21 CarPlay ETA数据入口测试版

APP99.0.21；地图服务99.0.18；渲染器99.0.15。仅APP更新，保持仓库99.0.20的地图效果；本地未完成的轮廓调整不包含在此包。

ETA优先读取ProjectedModeGuiding/Main_Instance.waypoints，结合CarPlayManager/CarPlayManagerInst1的projectedGuidanceActive和projectedGuidanceMetadataAvailable。选择终点数据，显示剩余时间、里程和到达时刻。兼容数字字符串、hour/hours和minute/minutes。只读，不发送CarPlay界面控制请求。

转向/车道入口暂未改变。不同手机地图是否提供数据待实车验证，不能保证高德、百度等均支持。

启用：启动手机导航，确认仪表地图已显示；在APP勾选独立到达时间卡片，按应用卡片设置。退出导航、元数据关闭或数据过期时隐藏。开关只在当前APP进程内生效，重启后需再次应用。

若不显示，请拍APP卡片状态，包含CarPlay连接、导航活动、元数据、waypoints和ETA识别情况。诊断不记录道路、路线或目的地内容。

已通过数据解码、CarPlay标志、无Guidance数据、过期/导航结束、模拟页面及Store模块链接和接口声明检查；尚未实车验证。未连接车机。

[安装包与源码](https://github.com/bimmerhub-tc/TC/releases/tag/99.0.21)
