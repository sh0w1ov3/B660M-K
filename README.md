### 硬件配置 OC0.91
| 硬件 | 型号                 |
| ---- | -------------------- |
| 主板 | Asus B660M-K         |
| CPU  | Intel i5 12500       |
| 内存 | 三星 DDR4 3200 16gx2 |
| 显卡 | Asus Dual RX6600 8g  |
| 硬盘 | SN850X 1T            |
| 无线 | BCM943602CS          |

![WechatIMG2](https://github.com/sh0w1ov3/B660M-K-i5-12500-RX6600/assets/33852403/4737144e-d70d-4631-9982-9235704148f7)

CFG Lock解锁：使用OC工具**modGRUBShell.efi**填入以下代码解锁：

`
setup_var_cv CpuSetup 0x44 0x01 0x00
`

BIOS设置：禁用 VMD Controller、串口、并口、安全引导、快速启动

RX6600免驱，务必使用第一个DP口连接显示器

不支持睡眠，请关闭睡眠功能
