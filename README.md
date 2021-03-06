This repository contains pre-compiled binaries of the current Raspberry Pi 
kernel and modules, userspace libraries, and bootloader/GPU firmware.

A rough guide to this repository and the licences covering its contents is 
below (check the appropriate directories for more specific licence details):

* boot:
    * start*.elf, fixup*.dat and bootcode.bin are the GPU firmwares and
    bootloader. Their licence is described in `boot/LICENCE.broadcom`.
    * The kernel.img files are builds of the Linux kernel, released under the GPL
    (see `boot/COPYING.linux`)
    * The dtbs, overlays and associated README are built from Linux kernel
    sources, released under the GPL (see `boot/COPYING.linux`)
* debug: pre-built modules for the kernel_debug.img (`boot/COPYING.linux`)
* documentation/ilcomponents: OpenMax IL documentation (`boot/LICENCE.broadcom`)
* extra: System.map files for the provided kernel builds (`boot/COPYING.linux`),
  and dt-blob.dts (`boot/LICENCE.broadcom`)
* hardfp/opt/vc: userspace VideoCoreIV libraries built for the armv6 hardfp ABI
  (`opt/vc/LICENCE`)
* modules: pre-built modules for kernel.img (`boot/COPYING.linux`)
*/ve: includes userspace libraries for the VideCoreIV - EGL/GLES/OpenVG 
  etc. (`opt/vc/LICENCE`)
* modules: make a change
