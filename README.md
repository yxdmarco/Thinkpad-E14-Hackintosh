# Thinkpad-E14-Hackintosh
Files and steps for Thinkpad E14 Hackintosh。

# Hardward Information:
- Processor : Intel Core(TM) i7-10510U
- RAM : 16GB DDR4 2667Mhz
- IGPU : Intel UHD 
- Storage : 1x HDD 1TB + 1x NVME 1TB
- Ethernet : Realtek RTL8168/8111 PCI-E Gigabit Ethernet Adapter
- Wifi : Intel Wi-Fi 6E AX210NGW 160MHz Wireless Network Adapter and Bluetooth
- Audio Codec : Conexant CX8070
- Input: ELAN Touchpad / TrackPoint + PS2 Keyboard
- Display : Lenovo NV140FHM-N48 13.9"
- Monitor Resolution : Full HD 1920 x 1080
- Boot Mode : UEFI

# Software Information:
- Bootloader : OpenCore r0.9.5
- OS Version : macOS 14.1 (23B74)

# Methond Used:
- OpenCore

```
sudo pmset -a hibernatemode 0
sudo pmset -a proximitywake 0
```
# Working Things:
- QE/CI Graphics Of iGPU Intel UHD , Metal 3
- CPU Power Management
- Shutdown, Restart, Sleep and Wake
- Internal Speaker, Headphone, External and Internal Mic
- Brightness
- Brightness Button Up/Down
- Touchpad / TrackPoint
- Ethernet
- Wifi
- Bluetooth
- Camera
- HDMI Out
- HDMI Audio
- Battery Indicator
- All USB Ports
- H264 Hardware Acceleration

# Not Working Things:
- FN + HotKey won't work after wake from sleep
- dGPU
- HEVC Hardware Acceleration

# ScreenShots:
- cpu power
![](https://github.com/yxdmarco/Thinkpad-E14-Hackintosh/blob/b90e91a69fc5b5b8b1aa7ec321b473ed98c2b4db/screenshot/01_about_status_cpu.png)
- wifi:
![](https://github.com/yxdmarco/Thinkpad-E14-Hackintosh/blob/017f5572446aaa4ad3b6601355516567b4b2e8f9/screenshot/02_about_pci_wifi.png)
# References:
- https://dortania.github.io/OpenCore-Install-Guide/
- https://www.reddit.com/r/hackintosh/comments/n132fg/lenovo_thinkpad_e14_sleepwake_and_hdmi_problem/
- https://github.com/AniKulkarn/Hackintosh-ThinkPad-E14
- https://github.com/pangzhen/ThinkPad-E14-Hackintosh
- https://www.installhackintosh.com/installed-hackintosh-system/1803-success-hackintosh-macos-ventura-13-5-1-build-22g90-in-lenovo-thinkpad-e14
- https://elitemacx86.com/threads/how-to-enable-h-264-and-hevc-h-265-encoding-on-macos.468/
