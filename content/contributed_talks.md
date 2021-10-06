+++
title = "Contributed talks"
description = "Contributed talks"
+++

**THE FOLLOWING TIMES ARE ALL JAPAN TIME**

## day1

### (time) Omar El-Ashkar: "rGenomeTracks: Extending epigenetic visualization methods in R"

High throughput sequencing technologies have been proved useful in a plethora of omics. Epigenomics is an area of active research that innovatively blends different biological techniques with sequencing to gain new insight into epigenetic regulations like chromatin accessibility, genome topology and nucleosome positioning. One of the cornerstones of analyzing such data is to be able to visualize it. R has been limited by the difficulty of visualizing epigenetic data in a quick way ought to data size. Hence we created rGenomeTracks, an R package based on pyGenomeTracks python package that offers customizable, publication-ready figures in a quick way. rGenomeTracks make it easier for R users to have a smooth workflow without the need of interacting with python.

### (time) Xinyi Lin: "Differential composition analysis of single-cell data"

Single cell profiling technology such as single-cell RNA-seq (scRNA-seq) enables high throughput discovery and characterisation of diverse cell types or cell states in a population of cells. This ability has given rise to new statistical problems in robust quantification and comparison of cell-type proportion.. It remains challenging to effectively detect differential compositions of cell types when comparing samples coming from different conditions or along with continuous covariates, partly due to the small number of replicates and high uncertainty of cell clustering. Here, we introduce a new statistical model, DCATS, for differential composition analysis in single cells in a framework of beta-binomial regression. It leverages a confusion matrix to correct the bias of clustering and allows pre-estimated parameters across all cell types to account for its uncertainty. It also allows us to regress out the influence of confounding covariates except for the condition factor. Through multiple simulated and experimental data sets, we demonstrate the high effectiveness of DCATS in identifying variable cell types in various experiment designs. Combining the differential genes analysis, cell-cell interaction analysis, and other scRNA-seq analysis, DCATS deepens our understanding of cell types differential composition and gain biological insight.

## day2

### (time) Mahmoud:

### (time) Pengyi Yang: "PhosR enables processing and functional analysis of phosphoproteomic data"

Mass spectrometry (MS)-based phosphoproteomics has revolutionized our ability to profile phosphorylation-based signaling in cells and tissues on a global scale.
In this talk, I will introduce PhosR, a set of tools and methodologies implemented in a Bioconductor R package to allow the comprehensive analysis of phosphoproteomic data.
PhosR enables processing steps such as imputation, normalization, and functional analysis such as kinase activity inference and signalome construction.
Together, PhosR facilitates interpretation and discovery from large-scale phosphoproteomic data sets.

## day3

### (time) Luke C. Gandolfo: "Untangling batch and biological effects with RLE plots"

Data visualisation is an essential part of analysing high-dimensional gene expression data, e.g. RNA-seq. One reason for such visualisation is to detect the presence of technical variation, e.g. batch effects, and to check the success of our attempts to remove such variation via normalisation.
However, in situations where the biological conditions of interest are significantly confounded with the factors producing technical variation, common visualisation approaches, e.g. PCA plots, can be poor tools, since such plots are sensitive to both technical and biological effects.
Relative log expression (RLE) plots, on the other hand, are sensitive to technical effects but insensitive, i.e. highly robust, to biological effects, making them an ideal tool for visualising the presence of technical variation in situations involving confounding.
RLE plots also have significant advantages over similar robust plots, e.g. boxplots.
These claims are demonstrated through the use of real data examples and statistical simulation.

### (time) Kozo Nishida: "BoF: Improving accessibility to Bioconductor in Japan"

Accessibility to Bioconductor's information resources varies greatly between English and other languages. Bioconductor users in Japan are not small, but the number of developers is significantly smaller than in Europe and the United States.
This BOF introduces attempts to improve accessibility to Bioconductor in Japan, along with the activities of BioPackathon, the Software Carpentry Japanese Team, and the Bioconductor Community Advisory Board.
BioPacakthon is a community that promotes bio software packaging and provides Bioconductor packaging information in Japanese. BioPackathon also organizes BioC Asia 2021 and has conducted survey to overcome language barriers.
The Software Carpentry Japanese Team is a community that localizes Carpentries teaching materials in Japanese.
Bioconductor is creating Carpentries-style teaching materials, and it is important for Bioconductor that Carpentries' activities become active in Japan.
The Bioconductor Community Advisory Board has a board member in Japan, and is planning to improve accessibility from Japan to Bioconductor in line with the CZI EOSS project.
In this BOF, the above will be explained in slides and the future prospects will be introduced.

## day4
 
### (time) Zuguang Gu: "spiralize: an R Package for Visualizing Data on Spirals"
 
The spiral layout has two major advantages for data visualization. First, it is able to visualize data with long axes, which greatly improves the resolution of visualization. Second, it is efficient for time series data to reveal periodic patterns. Here we present the R package spiralize that provides a general solution for visualizing data on spirals. spiralize implements numerous graphics functions so that self-defined high-level graphics can be easily implemented by users. The spiralize package is available at https://CRAN.R-project.org/package=spiralize.
 
