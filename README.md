# X-NUCLEO-IDB05A1

The X-NUCLEO-IDB05A1 is a Bluetooth Low Energy evaluation board based on the SPBTLE-RF BlueNRG-MS RF module.
The X-NUCLEO-IDB05A1 is compatible with the ST Morpho and Arduino UNO R3 connector layout 
(the user can mount the ST Morpho connectors, if required). The X-NUCLEO-IDB05A1 interfaces with the STM32 
microcontroller via the SPI pin, and the user can change the default SPI clock, the SPI chip select and 
SPI IRQ by changing one resistor on the evaluation board.

## Examples

There are several examples with the X-NUCLEO-IDB05A1 library.
* X_NUCLEO_IDB05A1_HelloWorld: This application provides a simple example of usage of the X-NUCLEO-IDB05A1 
Expansion Board. For testing the sketch, you can download on the playstore the "BlueNRG" application provided by STMICROELECTRONICS.
* X_NUCLEO_IDB05A1_BeaconDemo: This application shows how to use X-NUCLEO-IDB05A1 with the Beacon Service.
You can test this application by connecting it with your smartphone. On Android, donwload any Beacon Scanner Apps 
(e.g. iBeacon & Eddystone Scanner by flurp laboratories https://play.google.com/store/apps/details?id=de.flurp.beaconscanner.app).

## Dependencies

The X-NUCLEO-IDB05A1 library requires the following STM32duino library:

* STM32duino SPBTLE-RF: https://github.com/stm32duino/SPBTLE-RF

## Documentation

You can find the source files at  
https://github.com/stm32duino/X-NUCLEO-IDB05A1

The SPBTLE-RF datasheet is available at  
http://www.st.com/content/st_com/en/products/wireless-connectivity/bluetooth-bluetooth-low-energy/spbtle-rf.html
