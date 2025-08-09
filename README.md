# Looking for original BIOS dump for Dell 5430 Chromebook (Bernardino 14 board)

## Description

Hello!

I’m looking for the original full BIOS dump for a Dell 5430 Chromebook.

### Board details:
- **Motherboard marking:** Bernardino 14, 213189-1, YJ109$CA
- **Board DP/N:** 05NX1G
- **Chip:** W25Q256JVEQ / W25Q256JVEM
- **MO:** 41003550 VER: 1A
- **P/N:** 4910S4100063

I currently have a working BIOS dump, but it’s **MrChromebox** modified and does not have a functional ChromeOS Recovery Mode.
I also tried using the official ChromeOS recovery image from Google’s website, but it does not boot on my device.

Even with the help of ChatGPT-5 (we tried rebuilding the firmware step-by-step), we couldn’t make a clean working image that would boot ChromeOS normally with modifications.

### Request:
I specifically need the **complete dump from the W25Q256 chip** (all regions: descriptor, ME, EC, coreboot, etc.) from a working device with stock firmware.

If anyone owns the same board and can read the chip with a programmer (**CH341A**, **TL866**, etc.) and share the binary file, it would be greatly appreciated.


Thanks in advance!
