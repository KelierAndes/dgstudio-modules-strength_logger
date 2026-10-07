# 强度日志示例（DGStudio 模块）

最小完整示例模块：订阅引擎 `state` 事件，把每台设备 A/B 通道的强度变化写入应用日志。依赖：无（仅 Python 标准库）。

## 功能

- 订阅引擎 `state` 事件，把每台设备 A/B 通道的强度变化写入应用日志（每设备限速 1 条/秒，避免刷屏）。

## 安装

在 DGStudio「模块」页的在线列表（来自[模块市场仓库](https://github.com/KelierAndes/dgstudio-modules-market)）中获取本模块；也可手动把本仓库 `modules/<模块 id>/` 文件夹整个放入应用目录的 `modules/` 下。
