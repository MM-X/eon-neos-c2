NEOS
======

NEOS is the operating system for your C2.
【1+3t刷openpilot教程（c2，NEOS20）】 https://www.bilibili.com/video/BV1dnQhYnEZT/?share_source=copy_web&vd_source=25cfc82384a4467c4092b69e7f853bfd

Updates
------

This repo is for restoring or recovering your device.

## 前置安装条件
参考 https://github.com/dragonpilot-community/dragonpilot_wiki/blob/master/cn/how_to_flash_openpilot_on_windows.md
一直看到“下载运行一键安装脚本”之前

Restoring on macOS & Linux
------

1. Connect your comma two (via a USB-C to USB-A cable) or EON Gold (via a USB-mini-B to USB-A cable) to your computer
2. Open a terminal
3. Clone this repo `git clone https://github.com/MM-X/eon-neos-c2.git`, then `cd eon-neos`
4. Run `./download.py`
5. Put your device into fastboot mode by turning off your device, then holding volume down + power.
6. Run `./flash.sh` DO NOT DISCONNECT THE DEVICE!

Restoring on Windows
------
1. Install the Google USB driver for ADB (Android Debug Bridge)... https://developer.android.com/studio/run/win-usb
2. Connect your comma two (via a USB-C to USB-A cable) or EON Gold (via a USB-mini-B to USB-A cable) to your computer
3. Download and extract this repository
4. Download & install Python 3
5. Run download.py to download NEOS and flashing tools
6. Put your device into fastboot mode by turning off your device, then holding volume down + power.
7. Run flash.ps1 (right click, run with powershell). DO NOT DISCONNECT THE DEVICE!
