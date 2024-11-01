```
                                                       ▀▀▀▀▀     ▀▀▀▀▀          ▀▀█▀▀
                                                       ▄▀▀▀▄  ▄  ▄▀▀▀▄  ▄  ▄▀▀▀▄  █  ▄▀▀▀▄
                                                       █   █  █  █   █  █  █   █  █  █   █
                                                        ▀▀▀   █   ▀▀▀   █   ▀▀▀   ▀   ▀▀▀
                                                              █      ▄▄▄█▄▄▄    █   █  
                                                              ▀      █  █  █     █▄█
                                                            ▀▀▀▀▀    █  █  █      ▀
                                                                     ▀  ▀  ▀
▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄
       
```
# TOTEM split keyboard

TOTEM is 34 keys column-staggered split keyboard made by @geigeigeist. It uses the Seeed XIAO RP2040.

You can use this command to compile the firmware
`qmk compile -kb totem -km default`

## QMK Quickstart

0. (Install QMK and run `qmk setup` (inside the qmk terminal))

1. Create a fork of this repository
2. Inside your qmk_firmware folder, navigate to `keyboards`
```bash
cd keyboards
```
3. clone this repository into your qmk_firmware folder
```bash
git clone https://github.com/<your-username>/qmk-config-totem.git totem
```
(the `totem` in the end is important, do not change it)

5. Compile the firmware (inside the qmk terminal)
```bash
qmk compile -kb totem -km default
```