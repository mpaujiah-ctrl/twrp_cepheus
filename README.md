# Device tree for Mi 9 (codenamed _"cepheus"_)

### Device specifications

| Device                  | Xiaomi Mi 9                                                   |
| ----------------------: | :------------------------------------------------------------ |
| SoC                     | Qualcomm SDM855 Snapdragon 855                                |
| CPU                     | 1x2.84 GHz Kryo 485 + 3x2.4 GHz Kryo 485 + 4x1.8 GHz Kryo 485 |
| GPU                     | Adreno 640                                                    |
| Memory                  | 6GB / 8GB RAM (LPDDR4X)                                       |
| Shipped Android version | 9.0                                                           |
| Storage                 | 64GB / 128GB / 256GB UFS 2.1 flash storage                    |
| Battery                 | Non-removable Li-Po 3300 mAh                                  |

### Features 
**Works**

- Booting.
- **Decryption** (Android 12+)
- ADB
- MTP
- OTG
- Vibration

### Compile

You can find a full compile guide for OrangeFox [Here](https://wiki.orangefox.tech/en/dev/building)

_Lunch_ command :
```
lunch twrp_cepheus-eng && mka adbd bootimage
```

## Credits
- Thanks to @mauronofrio for initial [cepheus twrp tree](https://github.com/mauronofrio/android_device_xiaomi_cepheus)
- Thanks to @Pranav-Talmale for android 12.1 dynamimc-retrofit [raphael trees](https://github.com/Pranav-Talmale/android_device_xiaomi_raphael-twrp)
- Thanks to @chematelegram for the commits for [twrp_cepheus](https://github.com/chematelegram/twrp_cepheus)
- Thanks to @tribual for the commits for [twrp_cepheus](https://github.com/tribual/twrp_cepheus)
- Thanks to @raystef66 for the android 16 [cepheus device tree](https://github.com/crdroidandroid/android_device_xiaomi_cepheus)
- Thanks to @raystef66 for the [InfiniR kernel for cepheus](https://github.com/raystef66/kernel_xiaomi_cepheus)

### Copyright
 ```
  /*
  *  Copyright (C) 2022-2026 The OrangeFox Recovery Project
  *
  * This program is free software: you can redistribute it and/or modify
  * it under the terms of the GNU General Public License as published by
  * the Free Software Foundation, either version 3 of the License, or
  * (at your option) any later version.
  *
  * This program is distributed in the hope that it will be useful,
  * but WITHOUT ANY WARRANTY; without even the implied warranty of
  * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  * GNU General Public License for more details.
  *
  * You should have received a copy of the GNU General Public License
  * along with this program.  If not, see <http://www.gnu.org/licenses/>.
  *
  */
  ```
