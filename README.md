# Supplementary materials for the adjustable dispersion compensation unit paper

The original paper ***Compact and adjustable compensator for AOD spatial and temporal dispersion using off-the-shelf components*** can be found [*here*](https://github.com/Y-Akihiro/Dispersion-Compensation-Unit/blob/main/documents/ol-46-7-1644.pdf) or on [*Optics Letters*](https://doi.org/10.1364/OL.419682) (https://doi.org/10.1364/OL.419682).

## Description
This repository contains supplementary materials for the adjustable dispersion compensation paper under two direcotries:
* *documents* - contains the paper and a supplementary document.
* *data* - contains original .cvs data .
>>The autocorrelation data were recorded with an autocorrelator (FR-103TPM, FEMTOCHROME Research, Inc.) with an oscilloscope (Tektronix TDS2024C) in a .csv format. 
* *code* - contains MATLAB and Python codes used to analyze and plot data.

## Compensator Design & Parts List
The compact compensator was designed with Autodesk Inventor 2017. The only custom part is the baseplate and all the other parts were purchased from [*Thorlabs*](https://www.thorlabs.com/) and [*Wasatch Photonics*](https://wasatchphotonics.com/product/800-lmm-at-1030nm/).

The lists of parts are available under Item List folder.

## Software & Packages

The following software and packages were used for design and analysis:
* Autodesk Inventor 2017 and 2021
	* Used to design the compensation unit base plate and make a 3D model of the compensation unit.
* MATLAB 2020a
	* Used to analyze the original .csv file.
* Python 3.7
	* Packages: numpy, scipy, matplotlib
	* Used to analyze data (fitting) and make plots.

## Screenshots
Running `.py` and `.py` will generate Figure 2 and 3 in the paper as shown beow:



## License
TBA 


## Contact

Please contact me if you have any questions or find any bug/error.

Akihiro Yamaguchi - akihiro.yamaguchi@nyu.edu
