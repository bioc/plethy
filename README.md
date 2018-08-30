#plethy


Analysis of whole body plethysmography data in R. [![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.12570.png)](http://dx.doi.org/10.5281/zenodo.12570)

####INSTALLATION

A stable version is best obtained through Bioconductor:

if (!requireNamespace("BiocManager", quietly=TRUE))
    install.packages("BiocManager")
BiocManager::install("plethy")

The plethy package was first part of Bioconductor 2.13.

Any new features, refactoring, or bug fixes will be applied here first so those interested in the latest
experimental version can install from here using the devtools package after first installing the dependencies:

if (!requireNamespace("BiocManager", quietly=TRUE))
    install.packages("BiocManager")
BiocManager::install(c("RSQLite", "IRanges", "reshape2", "Streamer", "plyr"))  
install_github(username="dbottomly", repo="plethy", ref="master")

The package can also be installed manually by first clicking 'Download ZIP' and unzipping the resulting 'plethy-master.zip'
file into a convenient directory.  From within R in the same directory as 'plethy-master' type:

install.packages("plethy-master", repos=NULL, type="source")

####CONTRIBUTING

Contributions are encouraged through the standard fork/pull procedures.  Feel free to send me an email with any 
questions.

####BUG REPORTS, GENERAL QUESTIONS AND FEATURE REQUESTS

The Bioconductor mailing list is the best place to report bugs, ask questions or request features.

####MAINTAINER

Dan Bottomly  
bottomly@ohsu.edu
