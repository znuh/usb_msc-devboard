# devboard for USB mass storage
![Photo](https://user-images.githubusercontent.com/198567/226181044-9288992e-d87a-46f9-b368-dd583198cf9f.jpg)

## Parts
* MCU: [STM32F730R8Tx](https://www.st.com/en/microcontrollers-microprocessors/stm32f730r8.html) (or compatible)
* Mass storage: MicroSD via [DM3D-SF](https://www.hirose.com/product/series/DM3#) socket (attached to SDMMC1 of STM32)
* [USB3318](https://www.microchip.com/en-us/product/USB3318) USB high speed PHY
* 3.3V voltage regulator: [AP7313-33SR](https://www.diodes.com/part/view/AP7313/) or compatible
* PCB: 4 layer (Sig1, GND, 3.3V, Sig2) stackup
* 1x USB-C, 1x Micro USB
* 3x 0603 LEDs (power, user1, user2)
* 1x Button (Bootloader + user defined)
* passives: 0402 and 0603
* all componentes are on top, none on bottom

## Notes
* USB-C connector for hi-speed USB
* Micro USB connector for dev/debugging/DFU bootloader
* Testpads on bottom for UART (debugging, etc.)
