# 0xCB-Pluto

## Electrically and physically compatible with the standard Pro Micro featuring USB C, a flatter design for thight builds and preflashed with the QMK DFU bootloader for added stability.


Licence | OSHWA
:-------------------------:|:-------------------------:
![](https://github.com/0xCB-dev/0xcb-Pluto/blob/main/LICENSE.svg) | [![](https://github.com/0xCB-dev/0xCB-Pluto/blob/main/rev1.0/OSHWA.svg)](https://certification.oshwa.org/.html)

#### Flashing

* `qmk clone`
* `cd qmk_firmware`
* `export LTO=Y`
* To go to bootloader press the reset button.
* `make 0xcb/pluto:via:flash`

### Assembly:

You can use the [humanpnp](https://files.0xcb.dev/0xCB-Pluto/humanpnp.html) to easily place components.

### PCB:

KiCad 6 stable

[Schematic](https://github.com/0xCB-dev/0xcb-Pluto/blob/main/rev1.0/Pluto.pdf)

Top | Bottom
:-------------------------:|:-------------------------:
![](https://github.com/0xCB-dev/0xcb-Pluto/blob/main/rev1.0/Pluto.top.png)  |  ![](https://github.com/0xCB-dev/0xcb-Pluto/blob/main/rev1.0/Pluto.bottom.png)

#### BOM:

| References          | Value       | Quantity |Part Nb.          |
|---------------------|-------------|----------|------------------|
| C2, C3, C4, C5, C10 | 100n        | 5        |C478888           |
| C6, C9              | 1u          | 2        |C29936            |
| C7, C8              | 22p         | 2        |C85969            |
| C1                  | 10u         | 1        |C85713            |
| R5, R6, R8          | 10k         | 3        |C98220            |
| R1, R2              | 5.1k        | 2        |C23186            |
| R3, R4              | 22          | 2        |C174301           |
| R7, R9              | 330         | 2        |C104763           |
| D1                  | 1N4148WT    | 1        |C511874           |
| D2                  | WS2812B     | 1        |C114586           |
| U2                  | ATMEGA32U4  | 1        |ATMEGA32U4RC-MU-ND|
| U1                  | USBLC6-2SC6 | 1        |C7519             |
| Y1                  | 16MHz       | 1        |C389842           |
| F1                  | 1A          | 1        |C369150           |
| FB1                 | 600R        | 1        |C74330            |
| Q1                  | FDS9926A    | 1        |C693202           |
| J1                  | USB         | 1        |C168688           |
