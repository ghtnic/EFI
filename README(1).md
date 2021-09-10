# HP-ENVY-13-AH00012TX-Hackintosh-OpenCore

## 当前引导及系统版本

引导：OpenCore-0.7.2-RELEASE

系统：Big Sur 11.5.2（20G95）

## 硬件配置

| 配件 | 详情 | 工作状态 |
| :------: | :---------------------------: | :------: |
| 型号|HP-ENVY-13-AH0012TX| ☑️ |
| 主板 ID | HP 8482 | ☑️ |
| 处理器 | Intel i5-8250U（Kaby Lake Refresh） | ☑️ |
| 内存 | 8GB Dual LPDDR3 2133Mhz | ☑️ |
| SSD | ~~INTEL SSDPEKKF3360G7H(自带的360G)~~ / SN750 NVMe 500G） | ☑️ |
| 核芯显卡 | Intel UHD Graphics 620 | ☑️ |
| 声卡 | Realtek ALC285 | ☑️ |
| 无线网卡 | ~~Intel® Dual Band Wireless-AC 7265~~ / DW1560 | ☑️ |
| 显示器 | BOE077A 13.3" | ☑️ |

## 重要

- BIOS 设置为 默认，禁用 Secure Boot（安全启动）
- 注入新的 **三码**
- 不使用 **文件保险箱（FileVault）**
- 在 `系统偏好设置` -> `节能` 选项卡中，取消 `小憩` 和 `唤醒以供网络访问` 的勾选
- 在 `系统偏好设置` -> `蓝牙` -> `高级` 选项卡中，取消所有勾选

## 正常

- 扬声器    声音大小正常
- 读卡器    未使用
- 睡眠      正常
- 唤醒      正常
- CPU      正常
- USB      正常
- 缩放      正常（hidpi） --使用 [one-key-hidpi](https://github.com/xzhih/one-key-hidpi) 项目开启 **HiDPI**，以保护视力
- 核显      正常
- 键盘背光  正常（F5或Fn+F5）
- 屏幕亮度  正常
- 隔空投送   正常（更换为DW1560网卡）

## 非正常
- 独显150MX
- 触控板

## 注意
本人使用的笔记本已经更换了网卡和硬盘
自带网卡除了隔空投送等功能不能使用外，在使用intel驱动时还是可以正常使用的，自行更换驱动