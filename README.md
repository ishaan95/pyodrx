# pyodrx
pyodrx is a Python wrapper for generating OpenDRIVE 1.5 xml files. 
Please note that this is not an official implementation.

Work in progress, supported right now is creation of geometries, lanesections (with roadmarker), and junctions including some automation of 
roads that are connected with eachother.



## Getting Started

clone or download the repository.

### Prerequisites

Been tested with Python 3.6.9

### Installing

Go to the pyodrx folder and use

```
pip3 install .
```

### OpenDrive coverage 

OpenDrive coverage can be found in xodr_coverage.txt



## Related work

### esmini
[esmini](https://github.com/esmini/esmini) is a basic OpenSCENARIO player

### pyoscx
[pyoscx](https://github.com/pyoscx/pyoscx) basic python wrapper for OpenSCENARIO 

### scenariogeneration
[scenariogeneration](https://github.com/pyoscx/scenariogeneration) basic python wrapper to combine pyodrx and pyoscx to generate scenarios

### spirals

[pyeulerspiral](https://github.com/stefan-urban/pyeulerspiral), used this lib for calculating euler spirals

## Authors

* **Mikael Andersson** - *Initial work* - [mander76](https://github.com/mander76)

* **Irene Natale** - *Inital work* - [inatale93](https://github.com/inatale93)

## Data formats
The wrapper is based on the OpenDRIVE standard.