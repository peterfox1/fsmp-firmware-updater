
## FSMP Firmware Updater

### What is this?

This is a basic application for writing firmware to your FS Macro Panel. For now this is just to allow replacement Arduino modules to be setup if required.

This will be expanded in future to be able apply firmware updates to your device, ultimately this would all be incorporated into the controller application.

---

### Replacement Arduino Modules

If you are looking to replace the arduino module on your device, these are some of the options available:

#### ✔ Arduino Pro Micro (ATmega32u4) compatible module.

This is the orginal module used on FS Macro Panel and will be a direct replacement. This is a lower cost clone of the "Sparkfun Pro Micro". You will find these from local suppliers as well as Aliexpress or eBay.

 - Direct replacement, this will appear in the firmware updater without any additional steps.
 - Note: most of these modules will ship without the pins soldered by default. Pre-soldered options are available from some suppliers.
 
#### ✔ SparkFun Qwiic Pro Micro - USB-C (ATmega32U4) - DEV-15795

This is the best alternative if you want USB type-c, it requires sparkfun's USB driver but after that it should appear in the firmware updater.

 - Requires SparkFun's USB driver.

#### ⚫ Bit-C (& Elite-C)

This is a slightly lower cost option than the SparkFun Qwiic Pro Micro, however it wouldn't appear as a USB device for me and required programming via ISP. It may be possible to load the firmware via USB with the right drivers perhaps but I couldn't confirm this.

 - Didn't work right out of the box for me.
 - It worked after loading the Arduino Leonardo bootloader with an ISP programmer first.


