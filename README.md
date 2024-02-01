# Obins Anne Pro (v1) User Guide

I was gifted this keyboard and decided to write a proper English User Guide as a contribution back to the community for the blessing. I believe many people are still using this keyboard even though it’s rather old, and the only [other English user guide](https://service.hexcore.xyz/manual/annepro/) that exists is poorly translated from Chinese.

Tested with firmware 1.40.00.

## Bluetooth/setup mode

Enter setup mode by pressing FN+B. Pressing ESC or FN+B again exits the mode.

When in setup mode, the keys 1, 2, 3, 4, A, B, 0, - and + are lit.

Once in setup mode, press the following to configure specific settings:
* "+" - Enable bluetooth broadcast
* "-" - Disable bluetooth (radio off)
* FN+1, 2, 3 or 4 - Save current connection to a profile (1 thru 4) - bluetooth must be connected to device before saving
  * Red  = no device saved
  * Yellow = device saved
  * Green = current connected device
* 1, 2, 3 or 4 - Quick switch to a saved profile
* FN+0 - Switch between Bluetooth Low Energy (BLE) mode and normal mode
  * Green - BLE mode (discovered device name contains L0)
  * Yellow - Normal mode (discovered device name contains L1)
  * Takes about a second or two to switch after you press the key
* A - Enable/disable backlight auto-sleep (new in 1.40.00)
  * Green = Auto-sleep on (backlight will switch off after 1 minute)
  * Red = Auto-sleep off (backlight will not switch off)

## Switching layouts

The keyboard has four different layouts:
* Windows
* Windows with ALT/FN/Menu/? keys as arrows
* Mac (Alt and Win swapped)
* Not sure (undocumented)

How to switch modes:
* Press L CTRL + R CTRL
* Release CTRL while still holding the other down
* Tap the released CTRL key to cycle through the modes

You will see the numbers 1, 2, 3, 4 light up in green indicating the layout mode.

## FN mode lock

To activate FN lock (i.e. in FN mode):
* Press ALT+ALT
* Press ALT+ALT again to revert to normal mode

There are no visual indicators to tell if you are in FN lock mode.

## Backlight modes

Various backlight options are controlled through four function toggles:
* FN+R - Turn off/on backlight
* FN+T - Rate/speed change (for animated modes)
* FN+Y - Backlight brightness (10 levels)
* FN+U - Cycle through different backlight modes

Available modes:
* Static red
* Static yellow
* Static green
* Static cyan
* Static blue
* Static purple
* Static pink
* Static orange
* Static white
* Static blue/white/red (France flag)
* Static green/white/red (Italy flag)
* Static cyan with white middle row (row 3)
* Animated pulsing colour cycle
* Animated rainbow scrolling/marquee
* Random colour on keypress (fades away)
* Random colour on keypress (remains lit)
* Animated light spread on keypress
* Animated random colour on keys

## Win key disable

To disable the Win key (or Command key in Mac mode):
* FN+WIN - Disable the WIN key
* FN+WIN again to enable

There’s no visual indicator on whether the key is locked or not.
In Mac mode, FN+ALT locks the command key.

## DFU mode

DFU mode is required for upgrading firmware.

To enter DFU mode:
* Unplug the USB cable
* Hold ESC while poking the reset button behind the keyboard
* Connect the USB cable
