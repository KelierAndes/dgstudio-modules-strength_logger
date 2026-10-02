# 强度日志示例（strength_logger）

依赖：无（仅 Python 标准库）。

最小完整示例模块：订阅引擎 `state` 事件，把每台设备 A/B 通道的强度变化写入应用日志（每设备限速 1 条/秒，避免刷屏）。演示了鸭子类型模块类、`ctx.log` / `ctx.events` 基本用法与高频事件限速。

作为开发模板使用：复制本目录、改 `META.id` 与类名，按开发文档（[EXTENSIONS.md](https://github.com/KelierAndes/dgstudio-modules-market/blob/main/EXTENSIONS.md)）实现自己的联动逻辑。

## 安装

在 DGStudio「模块」页的在线列表中获取本模块，安装时自动读取本仓库
`requirements.txt` 并 pip 补装依赖，卸载 / 更新即热重载生效。
也可手动把本仓库 `modules/<模块 id>/` 文件夹整个放入应用目录的
`modules/` 下。
