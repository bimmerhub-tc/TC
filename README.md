# MGU 仪表地图试验发布源

MGU Store → Settings → Add source：`teddychow2014-afk/mgu-cluster-releases`，选择 **Releases**。

当前99.0.7是自定义布局试验版，未完成车机实测，显示效果仍在调试。安装前确认当前版本与依赖；三个组件配套更新。保留普通仪表、HUD、仪表+HUD及关闭选项。

本仓库仅存放安装包目录与发布说明；安装包、SHA256及对应源码位于catalog Release。原始项目为 https://github.com/robertnisipeanu/idrive-apps ，原作者与第三方许可证保留；未包含BMW专有oap-sdk，也不包含SSH密钥、账号授权或车辆备份。

**版本说明：** 99.x试验版高于普通上游0.x版本，切回上游前需处理版本关系。Store更新通过本源检查，不保证即时自动安装。车机必须能访问GitHub下载地址。

## 下载和添加源

安装包在 [Releases / catalog](https://github.com/teddychow2014-afk/mgu-cluster-releases/releases/tag/catalog)，不在Code文件列表。

- [cluster-render@99.0.4.tgz](https://github.com/teddychow2014-afk/mgu-cluster-releases/releases/download/catalog/cluster-render%4099.0.4.tgz)
- [waze-on-cluster@99.0.4.tgz](https://github.com/teddychow2014-afk/mgu-cluster-releases/releases/download/catalog/waze-on-cluster%4099.0.4.tgz)
- [robertn_waze_cluster@99.0.4.tgz](https://github.com/teddychow2014-afk/mgu-cluster-releases/releases/download/catalog/robertn_waze_cluster%4099.0.4.tgz)

在车机MGU Store添加 `teddychow2014-afk/mgu-cluster-releases`，选择 **Releases**，刷新后查看“仪表地图（自定义试验版）”。本发布为99.0.5，尚未完成实车布局验证。

## 99.0.5 更新

规则闭合内框：平顶平底、光滑两侧、无中间凹凸或圆孔，边缘羽化。请在Store刷新本源并更新三个99.0.5组件。

[99.0.5安装包与对应源码](https://github.com/teddychow2014-afk/mgu-cluster-releases/releases/tag/99.0.5)

## 99.0.6 更新

旧版造型平滑对称化并放大10%，左移16下移15；最外10%地图不透明度0至20%，向内渐变，显示原厂UI。请在Store刷新本源并更新三个99.0.6组件。

[99.0.6安装包与对应源码](https://github.com/teddychow2014-afk/mgu-cluster-releases/releases/tag/99.0.6)

## 99.0.7 更新

旧版造型平滑对称化并放大10%，左移16下移15；最外10%地图不透明度0至20%，向内渐变，显示原厂UI。请在Store刷新本源并更新三个99.0.7组件。

[99.0.7安装包与对应源码](https://github.com/teddychow2014-afk/mgu-cluster-releases/releases/tag/99.0.7)
