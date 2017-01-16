# QCW_MMC_PCB
PCB for MMC for QCW DRSSTC

- PCB for 12.4nF/6.4kV MMC using 32x 6.2nF/1600V B32672 TDK EPCOS capacitors. Can fit other 15mm lead spacing capacitors (e.g. up to 32x 15nF/1600V in B32672 series, or using every second row, up to 16x 33nF/1600V).
- Suggest using 2x >5Mohm 1206 High Voltage SMD resistors for bleed/balance across each capacitor (footprints provided on underside) 
- Footprints provided for optional Wurth Electronics press-fit connectors (assumes HASL PCB finish), as well as various holes for screw-down terminations
- Intended for use by itself (using 1 or more PCBs depending on requirement), or in conjuction with PCBs located in the "GDT_PCB" and "QCW_half_bridge_PCB" repos.
