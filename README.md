# RNA-seq of GR manipulation in A549 cells

This repository contains the RNA-seq processing and differential expression analysis for the paper 
Gazorpak*, Hugentobler* et al., "Harnessing PROTAC technology to combat stress hormone receptor activation".

Briefly, a novel custom-made GR-PROTAC is compared to 2 common inhibitors (Mifepristone and cort113176) both at baseline and upon Dex-mediated GR activation, demonstrating a higher specificity and superior blockage.

The code for the primary processing of the RNA-seq and differential expression analyses is available [here](https://github.com/ETHZ-INS/MG_A549), the results of which are available as a [SummarizedExperiment here](data/results/SE.processed.rds). The code for further downstream analyses, including the figures from the paper, are available in the [docs](docs).
