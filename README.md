This repository contains the hardware design files for the kinX mk66f keyboard
controller, a replacement controller for the Kinesis Advantage keyboard.

You can order this PCB at [OSH Park](https://oshpark.com/shared_projects/75qdnpC4).

You can order the components at [Mouser](https://www.mouser.ch/ProjectManager/ProjectDetail.aspx?AccessID=a9afbb88bc)

Note that the bootloader chip `IC_MKL04Z32_TQFP32` is not included in the BOM
and is only available from PJRC’s shop: https://www.pjrc.com/store/ic_mkl02.html

Also note that micro USB cables are not included in the BOM (you’ll need one for
power and firmware flashing, another one for USBHS data). I recommend building
the kinX hub, whose BOM includes the USB cables and which is a drop-in
replacement for the hub that comes in the Kinesis Advantage keyboard:
https://github.com/kinx-project/hub-hw
