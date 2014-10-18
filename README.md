# Building:
1. export PATH=<arm-eabi-4.7>/bin:$PATH
2. cd bootable/bootloader/lk
3. make PROJECT=msm8226 BOOTLOADER_OUT=../../../out/target/product/shellr/obj/BOOTLOADER_EMMC_OBJ EMMC_BOOT=1