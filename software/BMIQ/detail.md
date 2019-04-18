### BMIQ

**[R Script for BMIQ](./BMIQ/BMIQ_1.4.R)** This is the script of BMIQ

**[R Script for DoBMIQ](./BMIQ/DoBMIQ.R)** This is a script to run BMIQ on a set of Methylation Data.

To run BMIQ code, after placing all stuffs(data, probe information, annotation) in one folder, you can use following R code to calculate it out:
```
source("DoBMIQ.R")
```


**Or you can find BMIQ function in ChAMP Package, which is developed by Tiffany Morris**

**Installation**
To install ChAMP package, start R and enter:
```
source("http://bioconductor.org/biocLite.R")
biocLite("ChAMP")
```
