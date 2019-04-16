**[[SourceForge Link]](http://sourceforge.net/projects/signalentropy/files/?source=navbar)**

**DESCRIPTION OF FILES:**

**1) dataSCM2.Rd:** R data object file containing gene expression data matrix, avdataSCM2.m, from the stem cell matrix 2 compendium. Matrix is of size ~17000 genes X 191 samples. The type of cell (i.e hESC=1, iPSC=2 or somatic differentiated=3) is indicated in the phenoSCM2.lv[[1]] entry. Rownames of expression data matrix annotated to Entrez gene IDs.


**2) hprdAsigH-13Jun12.Rd:** R data object file with a model of PPI network specified by the adjacency matrix hprdAsigH.m. Rownames annotated to Entrez gene IDs.


**3) sr.Rd:** an auxiliary R object file needed to run the vignette.


**4) DoIntegPIN.R:** R-function to perform integration of a PPI network with a gene expression data matrix, extracting the maximally connected subnetwork.


**5) CompSR.R:** R-function to compute the entropy rate plus auxiliary functions.


**6) CompSRana.R:** R-function to compute the entropy rate analytically assuming detgailed balance (this will speed up the computation).


**7) [sigent.pdf:](./SignalEntropy/intro.pdf)** vignette/manual pdf.