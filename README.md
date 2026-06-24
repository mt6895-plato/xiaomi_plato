# Xiaomi 12T Local Manifest AOSP

### Android 16 QPR2 for Xiaomi 12T
Use this Local manifest to build your Custom ROM for Xiaomi 12T!\
To get started, place `plato.xml` into your custom rom local_manifests: `.repo/local_manifests/plato.xml`\
All credits and work goes to [Xiaomi MT6895 Devs](https://github.com/xiaomi-mt6895-devs) and [XagaForge](https://github.com/XagaForge).

Below is all of the sources used to build:
Required files   | Source
-------:|:-------------------------
Hardware     | [android_hardware_xiaomi](https://github.com/XagaForge/android_hardware_xiaomi) <br /> [android_hardware_mediatek](https://github.com/XagaForge/android_hardware_mediatek)
Device Trees | [android_device_xiaomi_plato](https://github.com/mt6895-plato/android_device_xiaomi_plato) <br /> [android_device_xiaomi_mt6895-common ](https://github.com/XagaForge/android_device_xiaomi_mt6895-common) <br /> [android_device_mediatek_sepolicy_vndr](https://github.com/XagaForge/android_device_mediatek_sepolicy_vndr)
Vendor Trees     | [android_vendor_xiaomi_mt6895-common](https://github.com/XagaForge/android_vendor_xiaomi_mt6895-common) <br /> [android_vendor_xiaomi_plato](https://gitlab.com/archcloudy/android_vendor_xiaomi_plato)
MiuiCamera (uncomment on plato.xml) | [android_device_xiaomi_plato-miuicamera](https://github.com/mt6895-plato/android_device_xiaomi_plato-miuicamera) <br /> [android_vendor_xiaomi_plato-miuicamera](https://github.com/archcloudy/android_vendor_xiaomi_plato-miuicamera)
Kernel Dependencies  | [android_kernel_xiaomi_mt6895](https://github.com/XagaForge/android_kernel_xiaomi_mt6895)

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core CPU with 4x Arm Cortex-A78 up to 2.85GHz
Chipset | Mediatek Dimensity 8100
GPU     | Mali-G610 MC6
Memory  | 8 GB RAM (LPDDR5 6400Mbps)
Shipped Android Version | 12
Storage | 128/256 GB (UFS 3.1)
Battery | Li-Po 5000 mAh, non-removable
Display | 1220 x 2712 pixels, 6.67 inches, 60/120hz

![Xiaomi 12T](https://i02.appmifile.com/898_operator_sg/26/08/2022/fc94660da1d6dd006f7589327bb72813.png)
