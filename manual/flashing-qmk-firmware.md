# Flashing QMK firmware

It's very simple and straightforward. Following the official guide would be enough.

The core steps:

1. Setup the QMK environment.
2. Build the firmware - `qmk compile -kb yandrstudio/yr6095 -km default`.
3. Put the board into DFU mode. There are 2 ways:
   - Bootmagic reset:
     1. Unplug the USB from the board.
     2. Hold down the key at (0,0) in the matrix (the top left key which is Escape on keyboard).
     3. Plug USB to the board.
   - Press the key mapped to `QK_BOOT` if available.
4. Flash the firmware - `qmk flash -kb yandrstudio/yr6095 -km default`.
5. Test it.

> Note: If you are sure that only the bootloader is currently flashed and there is no firmware, the device will automatically enter DFU mode, and you can skip step 3.
