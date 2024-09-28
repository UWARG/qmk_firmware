# qmk_firmware

This is the QMK configuration for a custom keyboard based on [this](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2FUWARG%2Fhardware%2Ftree%2Fmaster%2FProjects%2FIMACS%2FKeyboard%2FIMACS_Keyboard) design with a RP2040 as the microcontroller.

To flash the configuration onto a RP Pico:  

1. Run this command:  
`qmk flash -kb 60ansi_f24 -km default`  

2. Hold the **BOOTSEL** button on the RP Pico while connecting to the board.  

This will compile the firmware, then put the RP Pico into bootloader mode, and automatically flash the firmware onto the board once its connected.