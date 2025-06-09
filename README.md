# pcb-yr6095

The software and manual for [YR6095](https://github.com/qmk/qmk_firmware/tree/2e3664d2c005a36f06c567aa55702ac950866598/keyboards/yandrstudio/yr6095) PCBs.

This repo includes:

- software:
  - the bootloader
- manual：
  - [flashing bootloader](./manual/flashing-bootloader.md)
  - [flashing QMK firmware](./manual/flashing-qmk-firmware.md)
  - [about the matrix](./manual/about-the-matrix.md)

## About YR6095

- It's a PCB designed by [Y&R Studio](https://www.yrkb.cc/).
- It's GH60 compatible.
- It supports multi 60% layout, and there're 95 available keys.
- It supports hot-swap switch sockets.
- It supports PCB-mounted satellite switch.
- It has only one RGB LED in the position of CapsLock.
- It uses STM32F103CBT6 as the controller, but with 16mhz HSE.
- QMK has support for it.
