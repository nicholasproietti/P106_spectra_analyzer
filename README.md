# P106 Spectra Analyzer

The notebook provides the source code for all the analysis peformed on the spectra of hundreds of low-mass stars in the central clusters of the Carina Nebula for the ESO programme ID **106.212B.001**.

Note: Versions <8.5 of `P106_spectra_analyzer` have not been recovered from data loss and thus are not included.

## The data
The data can be downloaded from the ESO science archive: 
https://archive.eso.org/cms.html

The PID is [106.212B.001](https://archive.eso.org/wdb/wdb/eso/sched_rep_arc/query?progid=106.212B.001) (that link may take you straight to the dataset if google cooperates). 

## The pipeline
The [pipeline](https://eso.org/sci/software/pipelines/) to reduce data from GIRAFFE/FLAMES is available for installation from ESO.

## The source catalog
For reference, the source catalog -- where we identified the stars to observe -- is [Hur et al. 2012](https://ui.adsabs.harvard.edu/abs/2012AJ....143...41H/abstract). `table1.dat` lists the`IDs` of all sources in the catalog with spectral information. 

For example, the star named "998" from the data collected under 106.212B.001 should correspond to star 998 in the Hur et al. catalog. 
