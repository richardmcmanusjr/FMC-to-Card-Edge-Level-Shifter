# FMC-to-Card-Edge-Level-Shifter

This repository contains an 88 channel conversion board designed to interface an 88-pin probe card with a Virtex-7 VC707 FPGA via an FMC cable. Additional level shifting was required to lower the FPGAs 1.8V logic to 1.2V for 58 signals. Simple voltage dividers were chosen for this purpose.

# Details

Schematic File:
  - Created "Voltage Divider" Module
  
Board File:
  - Placed components manually
  - Ran autorouter to route tracers
  - Placed vias to generate ground plane throughout board
  - Ran Import_bmp.ulp to import graphics
 
# Design

<p align="center">
  <img src="https://github.com/richardmcmanusjr/FMC-to-Card-Edge-Level-Shifter/blob/main/BlockDiagram.png" width="450">
</p>

# Finished Layout 

<p align="center">
  <img src="https://github.com/richardmcmanusjr/FMC-to-Card-Edge-Level-Shifter/blob/main/F2CE_Social_Preview.png">
</p>

# Fabricated Board

<p align="center">
  <img src="https://user-images.githubusercontent.com/68760258/216797744-696944e2-cc38-4426-9f3e-8261d319e5d4.jpg" width="250">
</p>

