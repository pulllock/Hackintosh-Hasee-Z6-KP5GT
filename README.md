# Hackintosh-Hasee-Z6-KP5GT
Hackintosh Opencore EFI for Hasee Z6-KP5GT

# 系统版本

macOS Sequoia 15.4 (24E248)

# 硬件

- 型号：          神舟（Hasee）战神 Z6-KP5GT
- 处理器：       QuadCore Intel Core i5-7300HQ, 3100 MHz (31 x 100)
- 主板：           Notebook N85_N87,HJ,HJ1,HK1
- 主板芯片组：Intel Sunrise Point HM175, Intel Kaby Lake-H
- 独显：           GeForce GTX 1050  (2 GB)
- 集显：           Intel(R) HD Graphics 630  (1 GB)
- 网卡：           Realtek(R) PCI(e) Ethernet Controller （Realtek PCIe GbE Family Controller）
- 无线网卡：   Intel(R) Dual Band Wireless-AC 3168
- 蓝牙：           英特尔(R) 无线 Bluetooth(R)

# 硬件驱动

- CPU正常
- 独显屏蔽
- 集显正常
- 有线网卡正常
- 无线网卡：
	- 使用AirportItlwm无法正常驱动，AirportItlwm截止到2025-04-07只支持到Mac OS Sonoma 14
	- 替代方案：使用Itlwm驱动配合软件Heliport使用。
- 蓝牙正常
- 扬声器正常，可通过笔记本快捷键调整声音大小
- 耳机正常
- 麦克风正常
- 电池正常显示
- 电源适配器充电不显示
- USB正常
- 睡眠正常
	- 睡眠的设置需要在安装完系统后，在终端执行以下命令：
		- sudo pmset autopoweroff 0
		- sudo pmset powernap 0
		- sudo pmset standby 0
		- sudo pmset proximitywake 0
		- sudo pmset tcpkeepalive 0
- 笔记本键盘正常
- 键盘灯正常
- 触摸板正常
- 显示器亮度调节可用，笔记本快捷键Fn+F8、Fn+F9调节亮度不可用
- 摄像头正常
- miniDP接口未测试
- HDMI接口正常