# Supplementary materials for a compact and adjustable dispersion compensation unit

The original paper ***Compact and adjustable compensator for AOD spatial and temporal dispersion using off-the-shelf components*** can be found [*here*](https://github.com/Y-Akihiro/Dispersion-Compensation-Unit/blob/main/documents/ol-46-7-1644.pdf) or on [*Optics Letters*](https://www.osapublishing.org/ol/home.cfm) (https://doi.org/10.1364/OL.419682).

## Description
This repository contains supplementary materials for the adjustable dispersion compensation paper under the following directories:
* *documents* - contains the paper and a supplementary document.
* *baseplate design* - contains an Inventor (.ipt) file.
>>
<p align="center">
	<img width="40%" src="https://github.com/Y-Akihiro/Dispersion-Compensation-Unit/blob/main/img/baseplate.png">
	<img width="40%" src="https://github.com/Y-Akihiro/Dispersion-Compensation-Unit/blob/main/img/baseplate_sketch.png">
</p>

* *Item List* - contains the lists of items purchased from Thorlabs and Wasatch Photonics.
* *img* - contains images of the compensator design and the setup.

## Software & Packages

The following software and packages were used for design and analysis:
* Autodesk Inventor 2017 and 2021
	* Used to design the compensation unit base plate and make a 3D model of the compensation unit.
* MATLAB 2020a
	* Used to analyze the original .csv file.
* Python 3.7
	* Packages: numpy, scipy, matplotlib
	* Used to analyze data (fitting) and make plots.

## Compensator Design
The compact compensator was designed with Autodesk Inventor 2017. The only custom part is the baseplate and all the other parts were purchased from [*Thorlabs*](https://www.thorlabs.com/) and [*Wasatch Photonics*](https://wasatchphotonics.com/product/800-lmm-at-1030nm/).
The lists of purchased items are available under [*Item List*](https://github.com/Y-Akihiro/Dispersion-Compensation-Unit/tree/main/Item%20List).

A 3D model of the compensator was created on Inventor. The 3D models of the optical components (.sldprt files) were downloaded from [*Thorlabs*](https://www.thorlabs.com/) and converted to .ipt format.
<p align="center">
	<img width="60%" src="https://github.com/Y-Akihiro/Dispersion-Compensation-Unit/blob/main/img/Inventor_design.png">
</p>

The base plate was designed on Inventor and ordered from [*protolabs*](https://www.protolabs.com/).

## License
TBA 

## Contact

Please contact me if you have any questions or if you find any bug/error.

Akihiro Yamaguchi - akihiro.yamaguchi@nyu.edu
