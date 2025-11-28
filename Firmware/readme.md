# clein/galatea_old_type/rev_1_0

![PCB Top 3D View](/Asset/PCB_3D_Top.png)
![PCB Bottom 3D View](/Asset/PCB_3D_Bottom.png)

<br />

![PCB Top View](/Asset/PCB_Top.jpg)
![PCB Top View](/Asset/PCB_Bottom.jpg)

*A short description of the keyboard/project*

* Keyboard Maintainer: [Clein](https://github.com/Clein-KR)
* Hardware Supported: *The PCBs, controllers supported*
* Hardware Availability: *Links to where you can find this hardware*

Make example for this keyboard (after setting up your build environment):

    make clein/galatea_old_type/rev_1_0:via

Flashing example for this keyboard:

    make clein/galatea_old_type/rev_1_0:via:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
