# gcc-arm-embedded-build-armhf
GCC ARM embedded prebuild compiler for Raspberry Pi and Jetson TX2 
Source:https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads

## installation
### install on Raspberry Pi
install via raspberry pi terminal:
```bash
wget https://github.com/vanbwodonk/gcc-arm-embedded-build-armhf/releases/download/9-2019-q4-major/gcc-arm-none-eabi-9-2020-q1-update-armv7l-linux.tar.bz2
tar -xvf gcc-arm-none-eabi-9-2020-q1-update-armv7l-linux.tar.bz2
sudo cp -r gcc-arm-none-eabi-9-2020-q1-update/* /usr/
sudo rm -r gcc-arm-none-eabi-9-2020-q1-update
```

### install on Jetson TX2       
Aarch64 latest build from this repo is 8-2019-q3-update. I do not compile it anymore. Because ARM already released for it. Install via jetson TX2 terminal:

```bash
wget https://github.com/vanbwodonk/gcc-arm-embedded-build-armhf/releases/download/8-2019-q3-update/gcc-arm-none-eabi-8-2019-q3-update-linux-aarch64.tar.bz2
tar -xvf gcc-arm-none-eabi-8-2019-q3-update-linux-aarch64.tar.bz2
sudo cp -r gcc-arm-none-eabi-8-2019-q3-update/* /usr/
sudo rm -r gcc-arm-none-eabi-8-2019-q3-update
```
