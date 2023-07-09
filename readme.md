# Le Chiffre Keyboard - STM32 version
-----------

Open sourced design by tominabox1 updated to use stm32

## Changes  
* MCU: STM32F072CBT6 (128Kb flash, built-in DFU bootloader, crystal-less)
* RGB leds changed to SK6812 mini for voltage tolerance
* Roundeded PCB outline
* MX hotswap/Alps

## Firmware 
QMK and vial firmware are available

## Reset buttons
* DFU button is placed in the legacy reset button position. Plug in the board or push the reset button while DFU button is held down to enable DFU mode.

## Fabrication
* pcb dimensions: 84.96x227.34mm
* SK6812 mini 3535 has placement marker on "Data In" pin. Don't confuse it with sk6812-HS mini or sk6812 mini-E.
