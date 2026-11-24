# Encore

Encore 是面向 OPPO Enco X4 的 LE Audio（LC3）模块与管理器，适用于已适配的 ColorOS / OxygenOS 固件。

- 为 X4 请求 LE Audio 路由
- 显示编码、帧长、码率、传输时延和双耳链路质量
- 检查 LE Audio 前置条件，提供修复入口和日志导出

## 安装

1. 在模块仓库的 Releases 下载并安装 `encore.apk`。
2. 在支持 libxposed API 102 的 LSPosed 管理器中启用 Encore，勾选「蓝牙」（`com.android.bluetooth`）。
3. 授予 Encore Root 权限，然后在 Encore 中点「重启作用域」。

[源码、适配范围与使用说明](https://github.com/JustDreemurr/enco-x4-lc3-manager) · [反馈问题](https://github.com/JustDreemurr/enco-x4-lc3-manager/issues)
