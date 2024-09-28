# 60ansi_f24

![60ansi_f24]()

* A QMK configuration for a 60% keyboard RP2040 as the microcontroller*

* Keyboard Maintainer: [Harry Chen](https://github.com/Harry100089)
* Hardware Supported: *RP2040*
* Hardware Availability: *https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2FUWARG%2Fhardware%2Ftree%2Fmaster%2FProjects%2FIMACS%2FKeyboard%2FIMACS_Keyboard*

Make example for this keyboard (after setting up your build environment):

    make f24_efs:default

Flashing example for this keyboard:

    make f24_efs:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
