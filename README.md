Build instructions:

Download toolchain

make omap3621_gossamer_evt1c_defconfig
make uImage ARCH=arm CROSS_COMPILE=/path/to/toolchain/
make modules ARCH=arm CROSS_COMPILE=/path/to/toolchain/


