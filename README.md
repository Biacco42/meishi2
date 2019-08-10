# meishi2

**meishi2 - The updated micro macro keyboard.**

The micro macro keyboard which has only four keys for self-made keyboards beginners. 

![meishi](https://raw.githubusercontent.com/Biacco42/meishi2/readme/images/P7280566.jpg)

# Parts

- **1** meishi2 PCB
- **1** 5V/16MHz Pro Micro compatible boards
- **4** 1N4148 diodes
- **4** [Switches of your choice](https://mechanicalkeyboards.com/shop/index.php?l=product_list&c=107)
- **1** Tact switch
- **4** Cushion rubber

## Mount the Diodes

**Double check your work**. Black lines should be facing the square pad.

## Mount switches

Mount switches on PCB.

## Mount the Pro Micro

With the meishi2 PCB logo side up, mount Pro Micro upside up.

## Attach cushion rubber

Attach cushion rubber on PCB buttom side.

## Flash QMK Firmware

QMK firmware for meishi2 now abilable on [QMK official repo](https://github.com/qmk/qmk_firmware).
This document doesn't cover how to build QMK. Prease refer to [QMK documents](https://docs.qmk.fm/).

Connect the keyboard by usb cable to PC and run

```
$ make meishi2:default:avrdude
```

will build and try to flash your firmware. Follow the instractions that require to reset the Pro Micro.

This process may require privileges.

## All have done
