# KiCad Symbol Library for GPIB components

![Required KiCad Version](https://img.shields.io/badge/KiCad-%3E%3D7.0-success)
![Minimum KiCad Version](https://img.shields.io/badge/KiCad-=6.0-orange)
![License](https://img.shields.io/github/license/alba0404/gpib-kicad-library)
![Downloads](https://img.shields.io/github/downloads/alba0404/gpib-kicad-library/total)

This is a libray for KiCad 7.0 and above, may be compatible with version 6.0 of KiCad.
It contains symbols of components linked to the GPIB protocol (IEEE-488, also known by its old name HP-IB).

This library follows the [KiCad Library Convention](https://klc.kicad.org/).


## 1. Components
### 1.1 Symbols
#### 1.1.a gpib.kicad_sym
|Company|Component|Datasheet|Packages| 1st version |
|:------|:--------|:--------|:-------|:------------|
| NEC   | uPD7210 | [datasheet](https://datasheets.alba0404.fr/data/GPIB/uPD7210.pdf) | | 1.0.0 |
| NI    | NAT7210 | [datasheet](https://docs-be.ni.com/bundle/nat7210-4882chip-specs/raw/resource/enus/372012d.pdf) | | 1.0.0 |
| NI    | TMS9914ANL | [datasheet](http://www.bitsavers.org/components/ti/TMS9900/TMS9914A_General_Purpose_Interface_Bus_Controller_Data_Manual_Dec82.pdf) | | 1.0.0 |
| TI    | SN75160BN | [datasheet](https://www.ti.com/lit/ds/symlink/sn75160b.pdf) | DIP-20 | 1.0.0 |
| TI    | SN75160BDW | [datasheet](https://www.ti.com/lit/ds/symlink/sn75160b.pdf) | SOIC-20 | 1.0.0 |
| TI    | SN75161BN | [datasheet](https://www.ti.com/lit/ds/symlink/sn75161b.pdf) | DIP-20 | 1.0.0 |
| TI    | SN75161BDW | [datasheet](https://www.ti.com/lit/ds/symlink/sn75161b.pdf) | SOIC-20 | 1.0.0 |
| TI    | SN75162BN | [datasheet](https://www.ti.com/lit/ds/symlink/sn75162b.pdf) | DIP-22 | 1.0.0 |
| TI    | SN75162BDW | [datasheet](https://www.ti.com/lit/ds/symlink/sn75162b.pdf) | SOIC-24 | 1.0.0 |
| Intel | 8291A | [datasheet](https://w140.com/tekwiki/images/5/57/I8291A.pdf) | DIP-40 | 1.2.0 |
| Intel | 8292 | [datasheet](http://www.emuverse.ru/downloads/datasheets/other/intel/8292.pdf) | DIP-40 | 1.2.0 |
| Intel | 8293 | [datasheet](http://www.emuverse.ru/downloads/datasheets/other/intel/8293.pdf) | DIP-28 | 1.2.0 |
| Intel | 8296 | [datasheet](https://datasheet.datasheetarchive.com/originals/scans/Scans-004/Scans-0098874.pdf) | DIP-20 | 1.2.0 |
| Intel | 8297 | [datasheet](https://datasheet.datasheetarchive.com/originals/scans/Scans-004/Scans-0098874.pdf) | DIP-20 | 1.2.0 |
| National Semiconductor | DS75160AN | [datasheet](https://datasheets.alba0404.fr/data/GPIB/DS75160A.pdf) | DIP-20 | 1.3.0 |
| National Semiconductor | DS75160AWM | [datasheet](https://datasheets.alba0404.fr/data/GPIB/DS75160A.pdf) | SOP-20 | 1.3.0 |
| National Semiconductor | DS75161AN | [datasheet](https://datasheets.alba0404.fr/data/GPIB/DS75161A.pdf) | DIP-20 | 1.3.0 |
| National Semiconductor | DS75161AWM | [datasheet](https://datasheets.alba0404.fr/data/GPIB/DS75161A.pdf) | SOP-20 | 1.3.0 |
| National Semiconductor | DS75162AN | [datasheet](https://datasheets.alba0404.fr/data/GPIB/DS75162A.pdf) | DIP-22 | 1.3.0 |
| National Semiconductor | DS75162AWM | [datasheet](https://datasheets.alba0404.fr/data/GPIB/DS75162A.pdf) | SOP-24 | 1.3.0 |

#### 1.1.b Connector_GPIB
|Company|Component|Datasheet|Packages| 1st version |
|:------|:--------|:--------|:-------|:------------|
| L-com | CIB24S  | [datasheet](https://www.l-com.com/Images/Downloadables/2D/CIB24S_2D.pdf) | DIP | 1.1.0 |
| L-com | CIB24SPC | [datasheet](https://www.l-com.com/Images/Downloadables/2D/CIB24SPC_2D.pdf) | DIP | 1.1.0 |
| L-com | CIB24SRA | [datasheet](https://www.l-com.com/Images/Downloadables/2D/CIB24SRA_2D.pdf) | DIP | 1.1.0 |

### 1.2 Footprints
#### 1.2.a Connector_GPIB.pretty
|Company|Component|Datasheet|Packages| 1st version |
|:------|:--------|:--------|:-------|:------------|
| L-com | CIB24S  | [datasheet](https://www.l-com.com/Images/Downloadables/2D/CIB24S_2D.pdf) | DIP | 1.1.0 |
| L-com | CIB24SPC | [datasheet](https://www.l-com.com/Images/Downloadables/2D/CIB24SPC_2D.pdf) | DIP | 1.1.0 |
| L-com | CIB24SRA | [datasheet](https://www.l-com.com/Images/Downloadables/2D/CIB24SRA_2D.pdf) | DIP | 1.1.0 |

### 1.3 3Dshapes
#### 1.3.a Connector_GPIB.3dshapes
|Company|Component|Datasheet|Formats| 1st version |
|:------|:--------|:--------|:-------|:-----------|
| L-com | CIB24S  | [datasheet](https://www.l-com.com/Images/Downloadables/2D/CIB24S_2D.pdf) | step, wrl | 1.1.0 |
| L-com | CIB24SPC | [datasheet](https://www.l-com.com/Images/Downloadables/2D/CIB24SPC_2D.pdf) | step, wrl | 1.1.0 |
| L-com | CIB24SRA | [datasheet](https://www.l-com.com/Images/Downloadables/2D/CIB24SRA_2D.pdf) | step, wrl | 1.1.0 |


## 2. Contributions
Contributions are welcomed ! Please feel free to open an [Issue](https://github.com/Alba0404/gpib-kicad-library/issues) or a [Pull Request](https://github.com/Alba0404/gpib-kicad-library/pulls).  
Please follow the [KiCad Library Convention](https://klc.kicad.org/) in your Pull Requests.


## 3. License
gpib-kicad-library (c) by [Alexandre Barrat](https://github.com/Alba0404)  
This library is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/legalcode), with the following exception:
> To the extent that the creation of electronic designs that use 'Licensed Material' can be considered to be 'Adapted Material', then the copyright holder waives article 3 of the license with respect to these designs and any generated files which use data provided as part of the 'Licensed Material'.

[![CC BY-SA 4.0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/legalcode)

* 3D models and documentations for L-com connectors come from their website [https://www.l-com.com/](https://www.l-com.com/).

