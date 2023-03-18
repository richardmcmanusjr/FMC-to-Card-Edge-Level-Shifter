# FMC-to-Card-Edge-Level-Shifter

This repository contains an 88 channel conversion board designed to interface an 88-pin probe card with a Virtex-7 VC707 FPGA via an FMC cable. Level shifting was required to lower the FPGA's 1.8V logic to 1.2V. Resistor voltage dividers were chosen for this purpose.

# V3.1

- Resistor arrays used for voltage dividers
- Male header pins oriented at right angle to FMC connector
- Low quiescent current regulator implemented for 1.2V power supply
- Jumper for selecting power from FPGA or SMA

## Design

<p align="center">
  <img src="https://github.com/richardmcmanusjr/FMC-to-Card-Edge-Level-Shifter/blob/main/F2CE_V3.1/F2CE_V3.1_Main.png" height="275">
  <img src="https://github.com/richardmcmanusjr/FMC-to-Card-Edge-Level-Shifter/blob/main/F2CE_V3.1/F2CE_V3.1_Assembly.png" height="275">
</p>

## Layout 

<p align="center">
  <img src="https://github.com/richardmcmanusjr/FMC-to-Card-Edge-Level-Shifter/blob/main/F2CE_V3.1/F2CE_V3_Eagle.png" height="500">
</p>

<p align="center">
  <img src="https://github.com/richardmcmanusjr/FMC-to-Card-Edge-Level-Shifter/blob/main/F2CE_V3.1/F2CE_V3_OSHPARK.png" height="500">
</p>

# V2

- Discrete 0603 resistors used for voltage dividers
- Card edge connector oriented at right angle to FMC connector
- Optional SMAs for GND and Power
 
## Design

<p align="center">
  <img src="https://github.com/richardmcmanusjr/FMC-to-Card-Edge-Level-Shifter/blob/main/BlockDiagram.png" width="450">
</p>

## Layout 

<p align="center">
  <img src="https://github.com/richardmcmanusjr/FMC-to-Card-Edge-Level-Shifter/blob/main/F2CE_V2/F2CE_V2_Eagle.png" height="500">
</p>

<p align="center">
  <img src="https://github.com/richardmcmanusjr/FMC-to-Card-Edge-Level-Shifter/blob/main/F2CE_V2/F2CE_V2_OSHPARK.png" height="500">
</p>




