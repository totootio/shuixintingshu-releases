# 随心听书 · Android 发布页

本仓库**仅用于发布安装包产物**，不包含任何源代码。源码仓库为私有仓库。

## 下载

请前往 [Releases](https://github.com/totootio/shuixintingshu-releases/releases) 下载最新版本。

每个版本提供两个安装包：

| 文件 | 说明 |
|---|---|
| `shuixintingshu-v*.apk` | R8 混淆版（体积小、启动快，推荐大多数用户使用） |
| `shuixintingshu-v*-nmmp-hardened.apk` | nmmp dex2c 加固版（插件引擎方法体编译为 native 代码，防逆向；首次启动略慢） |

## 安装注意

- 部分 MIUI 安装器对从浏览器下载弹窗直接打开 APK 会报「解析包出现问题」——
  请从系统「文件管理」进入下载目录，点击 APK 安装。
- 版本覆盖安装即可，数据保留。
