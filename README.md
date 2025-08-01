# QEMU-iOS-NFS-Fix

QEMU-iOS is an emulator for legacy Apple devices.
Currently, the iPod Touch 1G and iPod Touch 2G are supported.

I added a patch onto nfs.c that allows this version to compile properly.

<img width="331" alt="it2g-qemu" src="https://github.com/devos50/qemu-ios/assets/1707075/9bf7f6c1-5918-47e9-bb3e-2e39ae15d519">

The schematic below shows the most important hardware components of the iPod Touch 2G and their interactions.
The schematic for the iPod Touch 1G is mostly similar.

<img width="80%" alt="it2g-schematic" src="https://github.com/devos50/qemu-ios/assets/1707075/4b8eca9a-74b0-4590-ad23-bc056acde434">

### Running the iPod Touch 1G

The iPod Touch 1G is unsupported in this build.

### Running the iPod Touch 2G

Instructions on how to run the iPod Touch 2G emulator can be found [here](https://github.com/winbamstudios/qemu-ios-nfs-fix/blob/ipod_touch_2g/RUNNING.md).
