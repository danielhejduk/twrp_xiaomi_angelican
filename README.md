# Android device tree for Redmi M2006C3MNG (angelican)

```
#
# Copyright (C) 2024 The Android Open Source Project
# Copyright (C) 2024 SebaUbuntu's TWRP device tree generator
#
# SPDX-License-Identifier: Apache-2.0
#
```

TWRP Official recovery checks:
```

- [ ] Not Working
- [X] Working
- [*] Not Tested

Blocking checks
- [X] Correct screen/recovery size
- [X] Working Touch, screen
- [X] Backup to internal/microSD
- [X] Restore from internal/microSD
- [X] reboot to system
- [X] ADB

Medium checks
- [*] update.zip sideload
- [*] UI colors (red/blue inversions)
- [X] Screen goes off and on
- [X] F2FS/EXT4 Support, exFAT/NTFS where supported
- [*] all important partitions listed in mount/backup lists
- [*] backup/restore to/from external (USB-OTG) storage (not supported by the device)
- [*] backup/restore to/from adb (https://gerrit.omnirom.org/#/c/15943/)
- [X] decrypt /data
- [X] Correct date

Minor checks
- [X] MTP export
- [X] reboot to bootloader
- [X] reboot to recovery
- [X] poweroff
- [X] battery level
- [X] temperature
- [X] encrypted backups
- [*] input devices via USB (USB-OTG) - keyboard, mouse and disks (not supported by the device)
- [*] USB mass storage export
- [X] set brightness
- [X] vibrate
- [*] screenshot
- [*] partition SD card
```
