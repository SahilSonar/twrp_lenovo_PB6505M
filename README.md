Device Tree for Lenovo Tab V7 (PB-6505M)
==========================================

The Lenovo Tab V7 (codenamed _"PB-6505M"_) is a mid-range phablet from Lenovo.
It was released in April 2019.

| Basic                   | Spec Sheet                                                                                                                     |
| -----------------------:|:------------------------------------------------------------------------------------------------------------------------------ |
| CPU                     | Octa-core                                                                                                                      |
| Chipset                 | Qualcomm Snapdragon 450 (SDM450)                                                                                               |
| GPU                     | Qualcomm Adreno 506, 650 MHz                                                                                                   |
| Memory                  | 3/4 GB RAM                                                                                                                     |
| Shipped Android Version | 9.0                                                                                                                            |
| Storage                 | 32/64 GB                                                                                                                          |
| Battery                 | Non-removable Li-Po 5180 mAh battery                                                                                           |
| Display                 | 1080 x 2160 pixels, 18:9 ratio (~350 ppi density)                                                                              |
| Camera (Back)(Main)     | 13 MP                                                                                                                          |
| Camera (Front)          | 5 MP                                                                                                                           |

## Device picture
![PB-6505M](https://fdn2.gsmarena.com/vv/pics/lenovo/lenovo-tab-v7-1.jpg)

## Build instructions

```
# Compiling
$ export ALLOW_MISSING_DEPENDENCIES=true
$ . build/envsetup.sh
$ lunch omni_PB6505M-eng
$ make -jx recoveryimage //replace x in -jx with number of cores you want to allot for compilation

```

**Copyright 2020 The Android Open Source Project**
