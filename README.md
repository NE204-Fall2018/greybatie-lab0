#NE 204 Report Lab0
This repo contains all the files necessary to build the lab report for NE 204 Lab O

Although this iteration does not use Becquerel, subsequent lab reports most likely will.

This repo also requires the packages "uncertainties" and "lmfit"


##Energy Calibration
Data was collected with a Coaxial HPGe detector with Am-241, Ba-133, Cs-137, Co-60, and Eu-152 sources. The MCA used to collect the dad had 13 bit resolution, yielding 8192 channels, stored in a single ASCII file.


Data: https://www.dropbox.com/s/hutmwip3681xlup/lab0_spectral_data.txt?dl=0
Checksum: https://www.dropbox.com/s/amumdrm9zp1kn8d/lab0_spectral_data.md5?dl=


A python script was written to conduct a two-point linear energy calibration using the 59.541 keV peak from Am-241 and the 661.657 keV peak from Cs-137. This calibration is then applied to the Ba-133 full energy peaks, and quantify the difference between the calibrated peak locations and the expected peak locations based on the literature.

##File instructions:

Downloading the data

Use the makefile to download the data for the lab:
```
make data
```

Validate data is not corrupted
```
make validate
```
Run Test on analysis code
```
make test
```
Generating the final report in pdf format
```
make
```
