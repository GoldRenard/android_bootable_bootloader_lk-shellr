# Building:
1. export PATH=prebuilts/gcc/linux-x86/arm/arm-eabi-4.7/bin:$PATH (add your toolchain to PATH var)
2. cd bootable/bootloader/lk
3. make PROJECT=msm8226 BOOTLOADER_OUT=../../../out/target/product/shellr/obj/BOOTLOADER_EMMC_OBJ EMMC_BOOT=1