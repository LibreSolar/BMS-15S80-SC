# BMS48V
Battery management system for up to 15 Li-ion cells based on bq76940 or bq76930 IC from Texas Instruments

## Features (updated version 10/2016):

- Up to 15 Li-ion cells (e.g. LiFePO4)
- Power circuit on separate board (see Switch-N-Sense repository)
- Balancing current approx. 150 mA
- STM32F072 ARM Cortex M0 microcontroller
- Built-in CAN communication interface and UEXT extension connector


## History

- Previous version was compatible to Arduino (based on ATmega 328P), but the processor was too small and didn't support CAN --> switched to STM32F072

(you can still find the old version by going back in the repository)