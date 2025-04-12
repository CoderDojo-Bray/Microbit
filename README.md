# Microbit

## Scratch or MakeCode

* Micro:bits can be used with either Scratch or MakeCode
* MakeCode tends to be easier to get up and running, since it will use WebUSB and works across Windows, Macs and Chromebooks equally
* Micro:bits on Scratch requires Scratch Link to run in the background, to pair Scratch with the Micro:bit over Bluetooth.
   * Scratch Link tends to be temperamental on Macs and does not exist for Chromebooks at all

## Projects

### MakeCode

* CoderDojo/Code Club's documented projects live at https://projects.raspberrypi.org/en/pathways/microbit-intro
* Additional retro arcade games can be found at https://arcade.makecode.com

## Preparing a Micro:bit Club Pack for CoderDojo

TIP: When updating multiple microbits (either firmware or Scratch) @conallob would save time by:
   * Downloading the relevant hex files and be ready to go
   * Use the same CLI copy command to copy the hex file over
   * Attach a micro:bit
   * Copy the hex file over
   * Disconnect micro:bit and attach the next micro:bit.

## Update the Micro:bit Firmware

1. [Download firmware](https://microbit.org/get-started/user-guide/firmware/),
   being careful to get firmware for the correct board version. (Firmware to Board mismatches
   will result in the
   [`529` Boot Error](https://support.microbit.org/support/solutions/articles/19000016969-micro-bit-error-codes))
3. Boot into Micro:bit bootloader, by holding down reset button (non LED grid side)
   **before** plugging in USB cable
5. Copy the `.hex` file onto the `MAINTAINENCE` drive
6. Wait for the yellow LED beside the reset button to stay solid
7. Disconnect and reconnect USB cable

## Install Scratch on Micro:bit

1. Download Scratch Micro:bit `.hex` from https://scratch.mit.edu/microbit & unzip
2. Boot the Micro:bit into Normal mode (appears as `NO NAME` device)
3. Copy `.hex` file into Micro:bit to `NO NAME` drive (**NB:** Make sure you are not in bootloader, you will confuse yourself)
4. Wait for the yellow LED beside the reset button to stay solid
5. Reboot Micro:bit
6. Confirm 5 letters are scrolling across the LED grid. This means it is ready to pair in Scratch
7. Pair with Scratch

## Additional Resources

* https://github.com/carlosperate/awesome-microbit/
   * In particular, https://github.com/carlosperate/awesome-microbit/blob/master/README.md#scratch-extensions
