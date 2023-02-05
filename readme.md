# Prebuilt Pytorch for ARM64 with Vulkan support
Goto [Release](https://github.com/raspiduino/pytorch-vulkan-arm-prebuilt/releases) tab to download

Built and tested on a Raspberry Pi 4B

Some note:
- Full build (including Vulkan SDK build, PyTorch build, and dependencies) takes about 7.5 GB
- Sometimes compiling **a single** C++ source file takes **more than** 2GB of RAM to complete, so you should try to reduce the parallel thread (eg decrease the `-j[NUMBER]` in your `cmake` build command) when you see `cc1plus` killed
- For those who wonder if this runs on `v3dv` Vulkan on RPi4, I can say that it **DOES NOT WORK**.

Thank you!
