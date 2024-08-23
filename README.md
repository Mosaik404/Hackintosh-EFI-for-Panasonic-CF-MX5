![截屏2024-08-23 14.26.18.png](https://github.com/Mosaik404/Hackintosh-EFI-for-Panasonic-CF-MX5/blob/main/%E6%88%AA%E5%B1%8F2024-08-23%2014.26.18.png)

# Hackintosh-EFI-for-Panasonic-CF-MX5

## 简介

一个经过初步验证的、暂时可以使用的、对于松下CF-MX5的黑苹果EFI

使用Rapid EFI配制而成。

**目前仅测试支持 MacOS 12 Monterey。**
**请前去Release下载文件**

## 硬件配置

### 基础硬件

- CPU：Intel Core i5-6300U
- 内存：4GB LPDDR3
- 显卡：Intel HD520
- WiFi：Intel AC8260
- 网卡：Intel I219-LM
- 声卡：<暂时未知，布局ID=12可以驱动>
  
  ### 外围硬件
- 摄像头
- 内置麦克风
- 读卡器
- 触控屏
  
  ### 输出接口
- 2×USB3
- VGA
- HDMi
- 3.5mm音频

## 已经驱动

- CPU

- 显卡

- WiFi/有线网卡/蓝牙

- 声卡/物理音量按钮

- 内置麦克风

- 摄像头

- 电池(包括损耗信息)+电源

- HDMI及声音

- USB3

- 背光控制

- 键盘/Fn音量大小、静音、亮度强弱功能键

- 触摸板(触摸板、键盘在睡眠之后无法正常使用)
  
  > “触摸板和键盘在睡眠之后无法正常使用，voodoops2.kext的问题”    ——引自[Panasonic_CF-SZ5_SZ5PDYVS_hackintosh_EFI/README.md at master · waldoxhm/Panasonic_CF-SZ5_SZ5PDYVS_hackintosh_EFI (github.com)](https://github.com/waldoxhm/Panasonic_CF-SZ5_SZ5PDYVS_hackintosh_EFI/blob/master/README.md)

## ToDo

- 驱动触控屏
- 驱动读卡器
- 尝试解决触摸板、键盘休眠问题

## 特别感谢

- [RapidEFI-Tool](https://github.com/JeoJay127/RapidEFI-Tool)
- 将黑苹果教程、资源等公开在互联网上的技术大佬们
