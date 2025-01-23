## Rembrandt Project - Personal extras
<img align="right" width="180" height="180" src="https://github.com/RembrandtProject/.github/blob/main/profile/RedmiK60E.png">

This organization contains repositories to build AOSP ROMs for Redmi K60E (rembrandt) with personal additions and modifications over [xiaomi-mediatek-devs](https://github.com/xiaomi-mediatek-devs) and [XagaForge](https://github.com/XagaForge) trees.

### Repositories
* [**Device Tree (rembrandt)**](https://github.com/RembrandtProject/android_device_xiaomi_rembrandt.git) (`android_device_xiaomi_rembrandt`)
* [**Device Tree (mt6895)**](https://github.com/RembrandtProject/android_device_xiaomi_mt6895-common.git) (`android_device_xiaomi_mt6895-common`)
* [**Vendor Tree (mt6895)**](https://github.com/XagaForge/android_vendor_xiaomi_mt6895-common.git) (`android_vendor_xiaomi_mt6895-common`)
* [**Kernel Tree**](https://github.com/RembrandtProject/android_kernel_xiaomi_mt6895.git) (`android_kernel_xiaomi_mt6895`)
* [**Firmware Tree**](https://github.com/RembrandtProject/android_vendor_firmware.git) (`android_vendor_firmware`)

Repositories such as `android_hardware_mediatek`, `android_hardware_xiaomi` and `android_device_mediatek_sepolicy_vndr` remain unmodified and can be used directly from the [xiaomi-mediatek-devs](https://github.com/xiaomi-mediatek-devs) organization.


### External patches
* [compat: expose android.hardware.sensors@1.0-convert as shared lib](https://review.lineageos.org/c/400894)
* [sensors: Add a sensors 2.0 -> 1.0 subhal wrapper](https://github.com/bengris32/android_hardware_lineage_interfaces/commit/cacfae73e44d18f8bba2bbe327d5c0d5cbafe4f1)
* [vendor: Add fastboot packages build](https://github.com/AresOS-UDC/vendor_lineage/commit/19afe7c7e98c9ff5f57c57d09edfa954142e65b6) (Only required if you choose to build fastboot packages using our method)
