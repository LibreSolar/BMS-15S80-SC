# BMS48V
Battery management system for up to 15 Li-ion cells based on bq76940 or bq76930 IC from Texas Instruments

Please find a good description about system integration of the BMS in the [Open Source Ecology Wiki](https://wiki.opensourceecology.de/24-48V_BMS) (in German).

## Features (updated version 03/2022):
- implemented new plug (Würth 66202021022) to connect accumulator cells to PCB. This modification was necessary in order to ensure correct behaviour of measuring the cell voltage with BQ76940. Cell tap number C10 was dividied into C10/C10.1 and C5 into C5/C5.1.
- correct connection of CAN IC
- adapt board dimension to fit into following cap rail casing:
Apra Rail F06 open or M06 open 107*90*48 mm

ordering for example here:
https://www.reichelt.de/leergehaeuse-db6-fmh-
90-x-107-x-33-mm-apra-fo6-o-p251001.html?
&trstct=pos_3&nbc=1


## Features (updated version 10/2016):

- Up to 15 Li-ion cells (e.g. LiFePO4)
- Power circuit on separate board (see Switch-N-Sense repository)
- Balancing current approx. 150 mA
- STM32F072 ARM Cortex M0 microcontroller
- Built-in CAN communication interface and UEXT extension connector

## History

- Previous version was compatible to Arduino (based on ATmega 328P), but the processor was too small and didn't support CAN --> switched to STM32F072

(you can still find the old version by going back in the repository)

