# TC 仪表大屏地图投射

当前APP99.0.16为卡片接口测试；两个底层组件保留99.0.15。

# 99.0.16 CarPlay 卡片接口测试版

基于99.0.15，仅更新APP。cluster-render与waze-on-cluster继续使用99.0.15；地图尺寸、位置、轮廓、边缘透明和自动投射代码未改变。

APP的CarPlay区域新增转向卡片、到达时间选项，以及“应用卡片测试”“恢复原卡片请求”和结果状态。选择后手动应用，启动时不自动发送测试请求。

通过车机原有CarPlayManager.requestProjectedScreen请求手机原生卡片。这条接口是否能控制仪表第二屏尚未实车验证。“接口已接受”不代表已经显示。不同地图可能忽略参数。本版尚不具备独立车道绘制、卡片30–40%不透明度或独立缩放功能。

卡片请求、HMI页面、原控制54/54及驾驶员设置21/21测试通过，安装包CRC/版本检查通过。未实车验证，不保证显示效果。没有远程操作车机。

Store源：bimmerhub-tc/TC，Releases，检查更新；只更新APP到99.0.16，底层两个组件保持99.0.15。
离线4.8工具选择_large.src.tgz安装包。详细步骤见instructions.txt。


[安装包、对应源码和预览](https://github.com/bimmerhub-tc/TC/releases/tag/99.0.16)
