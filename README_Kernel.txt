1. How to Build
  - get Toolchain
      From Android Source Download site( http://source.android.com/source/downloading.html )
      Toolchain is included in Android source code.

  - edit Makefile	
      edit "CROSS_COMPILE" to right toolchain path(You downloaded).
      Ex) CROSS_COMPILE = /opt/toolchains/arm-eabi-4.6/bin/arm-eabi-    // You have to check.
                    
  - Use arm-eabi-4.6 Version(toolchain)
  - Extract kernel source and move into the top directory.
  - Modify Makefile for the Arm Path(arm-eabi-4.6) according to your computer environment 
  - Execute ./make_kernel_GT-S7562C.sh
          
2. Output files
  - Kernel : kernel/arch/arm/boot/zImage