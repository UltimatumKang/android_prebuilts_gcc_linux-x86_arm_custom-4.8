android_prebuilts_gcc_linux-x86_arm_custom-4.8
==============================================
Custom toolchain configured and compiled with linaro gcc using crosstool-NG

Add this to your BoardConfig.mk or BoardConfigCommon.mk

TARGET_KERNEL_CUSTOM_LINARO_TOOLCHAIN := custom-4.8/bin/arm-cortexa9_neon-linux-gnueabihf-

Make cure to not have a duplice line such as TARGET_KERNEL_CUSTOM_TOOLCHAIN := 4.8 or the likes
