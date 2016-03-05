# BMS48V
Battery management system for up to 15 Li-ion cells based on bq76940 or bq76930 IC from Texas Instruments

## Features:

- Up to 15 Li-ion cells (e.g. LiFePO4)
- Current approx. 50A (terminals allow only 32A so far)
- FDMT80080DC as CHG and DSG FETs (same as new SBMS100 from Dacian Todea)
- High-side switches using new TI BQ76200 --> no problems with ground offsets for CAN communiction etc. anymore.
- Possibility of pre-charging the 48V bus before switching on the battery.
- Balancing current approx. 150 mA
