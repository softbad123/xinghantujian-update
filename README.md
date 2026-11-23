# 星汉图鉴 · 官方更新通道

本仓库发布星汉图鉴的程序安装包与更新清单，不包含解包数据或用户数据。

## 当前版本

- 显示版本：`2.2.261123`（2026年11月24日）
- 版本说明：https://github.com/softbad123/xinghantujian-update/releases/tag/v2.2.261123
- 更新清单（始终指向最新版）：https://github.com/softbad123/xinghantujian-update/releases/latest/download/update.json
- 本版安装包：https://github.com/softbad123/xinghantujian-update/releases/download/v2.2.261123/XingHanTuJian_Setup_v2.2.261123.exe
- 安装包大小：158,651,360 字节
- 安装包 SHA-256：`98E4B0ADC2E81091D41CC0045BAAA68D3645CF98757A41DFFA5B95FB58B1A56B`

动态皮肤新增 MP4 视频导出；GIF、APNG、MP4 均提供高画质、标准、小体积三档，分别采用最高 1280/960/640 像素宽度与 30/20/12 帧每秒。修复预览窗口关闭后的回调异常，以及成功导出文件被误删的问题。

## 自动更新

自 `2.2.20261102` 起，程序默认读取本仓库的 `latest/download/update.json`，普通用户无需填写更新源地址。可在「设置 · 软件更新」中关闭自动检查或自动安装。

本版显示版本为 `2.2.261123`，更新排序版本为 `2.3.2611230`；程序按更新排序字段识别新版本，不按显示版本的位数判断。

`2.2.20261101` 及更早版本需要先手动下载安装一次，此后可使用自动更新。普通升级请安装到原目录，并保留自己的配置、素材和导出文件。

安装前会核对清单中的包大小与 SHA-256；校验不通过时停止更新。
