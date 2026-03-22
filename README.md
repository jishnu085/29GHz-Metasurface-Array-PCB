# 29GHz-Metasurface-Array-PCB
Translation of a 29 GHz metasurface array from HFSS design to a fabrication-ready PCB layout using KiCad.


# 29 GHz Metasurface 10×10 Unit Cell Array – PCB Layout

## Overview

PCB implementation of a 29 GHz metasurface unit cell. The geometry was taken from an optimized HFSS design and converted into a manufacturable layout using KiCad.

## Design Preview

### HFSS Design
![HFSS Design](Antenna Layout/Screenshot 2026-03-22 214839.png)
### Unit Cell Geometry
![UnitCell](Antenna Layout/Screenshot 2026-03-17 200521.png)
### KiCad PCB Layout
![PCB Layout](Antenna Layout/Screenshot 2026-03-17 195727.png)
## 3D View
![3D View](Antenna Layout/Screenshot 2026-03-17 201236.png)

## Workflow

* Exported unit cell geometry from HFSS (DXF)
* Imported into KiCad
* Converted into solid copper (F.Cu)
* Designed 2-layer PCB with bottom ground plane

## Details

* Frequency: 29 GHz
* Structure: Microstrip (patch + ground)
* Tools: HFSS, KiCad

## Note

This work focuses on PCB layout implementation of a pre-optimized design.
