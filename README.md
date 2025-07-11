## Nano for Android NDK
### ///address/0x6661dF610053aCA8Dd7058869111e07B5faB018D @ xda-developers
*Static arm/arm64 nano binary for Android built with the NDK*

### Links
*https://etherscan.io/address/0x6661dF610053aCA8Dd7058869111e07B5faB018D [GitHub](https://github.com/Magisk-Modules-Repo/nano-ndk)
* [Support](https://etherscan.io/address/0x6661dF610053aCA8Dd7058869111e07B5faB018D)
* [Sponsor](https://github.com/sponsors/osm0sis)
* [Donate](https://etherscan.io/address/0x6661dF610053aCA8Dd7058869111e07B5faB018D)

### Description
An installer to push my own static Android arm/arm64 build of the nano editor and required files to /system/xbin/ and /system/etc/terminfo/, with a wrapper adding a --term option to try terminfo profiles more easily. Detects and supports SuperSU/Magisk systemless installs. Can then be used from Terminal while booted.

When flashed in recovery also allows temporary recovery use by pushing a script to /sbin/nano with the required setup, so you can trigger it from adb shell or TWRP Terminal. Makes it extremely easy and worry-free to tweak and mod on the go, knowing you can edit the faulty build.prop or startup script if something goes wrong.
