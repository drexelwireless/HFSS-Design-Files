# HFSS Project 3.5GHz RALA: This HFSS projcect has three files, each representating three modes of the reconfigurable Alford loop
antenna (RALA) at 3.5 GHz- i) Single mode (only one antenna element active), ii) dual mode: two
consecutive antenna elements active, diagonal radiation, and iii) omni mode: all four antenna
elements are active, omnidirectional radiation pattern. The antenna is fed with a 50 Ohm coaxial 
feed. Frequency sweep can run from 2.5 GHz to 4.5 GHz.

# 3p5GHz_RALA_Fabrication_PCBway.zip: Gerber files for fabrication. It can directly be submitted
to PCBway or any other PCB manufacturers. The thickness of the FR4 substrate is 1.6 mm.

# 3.5GHz RALA Population > BOM_RALA_PCBway.xlsx: This is the bill of materials. This is one of the
files needed for populating the antenna with the SMD components (inductor, PIN diode, LED, resistor).

#  3.5GHz RALA Population > Centroid_RALA: Centroid/pick-and-place file for placing the SMD comonents
on the PCB. This file should also be supplied to PCBway/manufacturers. 

# Ater population, a 50 Ohm SMA connector (with inner conductor diameter 1mm) should be inserted through
the central hole. The large circle on the top layer would be connected to the SMA ground (outer shell).

# Six jumper wires should be connected on six holes. 

# CST Mirowave Studio or other RF simulator user can import the gerber files from the 3.5GHz RALA 
Fabrication folder.

```
Paper to be cited:
@article{tajin2021, 
title={On the Design of Pattern Reconfigurable Alford Loop Antennas}, 
journal={International Conference on Electromagnetics in Advanced Applications (ICEAA)}, 
author={Tajin, Md Abu Saleh and Dandekar, Kapil R.},
year={2021}, 
month={Aug},
note={"to appear"}
}
```
