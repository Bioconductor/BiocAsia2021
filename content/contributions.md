+++
title = "Contributed talks"
description = "Contributed talks"
+++

**THE FOLLOWING TIMES ARE ALL JAPAN TIME (UTC+09:00)**

## Day1

### (15:00~) Omar El-Ashkar: "rGenomeTracks: Extending epigenetic visualization methods in R"

High throughput sequencing technologies have been proved useful in a plethora of omics. Epigenomics is an area of active research that innovatively blends different biological techniques with sequencing to gain new insight into epigenetic regulations like chromatin accessibility, genome topology and nucleosome positioning. One of the cornerstones of analyzing such data is to be able to visualize it. R has been limited by the difficulty of visualizing epigenetic data in a quick way ought to data size. Hence we created rGenomeTracks, an R package based on pyGenomeTracks python package that offers customizable, publication-ready figures in a quick way. rGenomeTracks make it easier for R users to have a smooth workflow without the need of interacting with python.

- https://github.com/OAshkar/rGenomeTracks

### (15:30~) Xinyi Lin: "Differential composition analysis of single-cell data"

Single cell profiling technology such as single-cell RNA-seq (scRNA-seq) enables high throughput discovery and characterisation of diverse cell types or cell states in a population of cells. This ability has given rise to new statistical problems in robust quantification and comparison of cell-type proportion.. It remains challenging to effectively detect differential compositions of cell types when comparing samples coming from different conditions or along with continuous covariates, partly due to the small number of replicates and high uncertainty of cell clustering. Here, we introduce a new statistical model, DCATS, for differential composition analysis in single cells in a framework of beta-binomial regression. It leverages a confusion matrix to correct the bias of clustering and allows pre-estimated parameters across all cell types to account for its uncertainty. It also allows us to regress out the influence of confounding covariates except for the condition factor. Through multiple simulated and experimental data sets, we demonstrate the high effectiveness of DCATS in identifying variable cell types in various experiment designs. Combining the differential genes analysis, cell-cell interaction analysis, and other scRNA-seq analysis, DCATS deepens our understanding of cell types differential composition and gain biological insight.

- https://github.com/huangyh09/DCATS/

## Day2

### (15:00~) Mahmoud Ahmed: "LINPS: a database for cancer-cell-specific perturbations of biological networks"

Screening for potential cancer therapies using existing large datasets of drug perturbations requires expertise and resources not available to all.
This is often a barrier for lab scientists to tap into these valuable resources.
To address these issues, one can take advantage of prior knowledge especially those coded in standard formats such as causal biological networks (CBN).
Large datasets can be converted into appropriate structures, analyzed once and the results made freely available in easy-to-use formats.
We used the Library of Integrated Cellular Signatures to model the cell-specific effect of hundreds of drug treatments on gene expression.
These signatures were then used to predict the effect of the treatments on several CBN using the network perturbation amplitudes analysis.
We packaged the pre-computed scores in a database with an interactive web interface.
The intuitive user-friendly interface can be used to query the database for drug perturbations and quantify their effect on multiple key biological functions in cancer cell lines.
In addition to describing the process of building the database and the interface, we provide a realistic use case to explain how to use and interpret the results.
To sum, we pre-computed cancer-cell-specific perturbation amplitudes of several biological networks and made the output available in a database with an interactive web interface.

- https://doi.org/10.1093/database/baab048

### (15:30~) Pengyi Yang: "PhosR enables processing and functional analysis of phosphoproteomic data"

Mass spectrometry (MS)-based phosphoproteomics has revolutionized our ability to profile phosphorylation-based signaling in cells and tissues on a global scale.
In this talk, I will introduce PhosR, a set of tools and methodologies implemented in a Bioconductor R package to allow the comprehensive analysis of phosphoproteomic data.
PhosR enables processing steps such as imputation, normalization, and functional analysis such as kinase activity inference and signalome construction.
Together, PhosR facilitates interpretation and discovery from large-scale phosphoproteomic data sets.

- https://bioconductor.org/packages/release/bioc/html/PhosR.html
- https://github.com/PYangLab/PhosR
- https://pyanglab.github.io/PhosR/

## Day3

### (15:00~) Luke C. Gandolfo: "Untangling batch and biological effects with RLE plots"

Data visualisation is an essential part of analysing high-dimensional gene expression data, e.g. RNA-seq. One reason for such visualisation is to detect the presence of technical variation, e.g. batch effects, and to check the success of our attempts to remove such variation via normalisation.
However, in situations where the biological conditions of interest are significantly confounded with the factors producing technical variation, common visualisation approaches, e.g. PCA plots, can be poor tools, since such plots are sensitive to both technical and biological effects.
Relative log expression (RLE) plots, on the other hand, are sensitive to technical effects but insensitive, i.e. highly robust, to biological effects, making them an ideal tool for visualising the presence of technical variation in situations involving confounding.
RLE plots also have significant advantages over similar robust plots, e.g. boxplots.
These claims are demonstrated through the use of real data examples and statistical simulation.

- https://doi.org/10.1371/journal.pone.0191629

### (15:30~) Kozo Nishida: "[BoF] Improving accessibility to Bioconductor in Japan"

Accessibility to Bioconductor's information resources varies greatly between English and other languages. Bioconductor users in Japan are not small, but the number of developers is significantly smaller than in Europe and the United States.
This BOF introduces attempts to improve accessibility to Bioconductor in Japan, along with the activities of BioPackathon, the Software Carpentry Japanese Team, and the Bioconductor Community Advisory Board.
BioPacakthon is a community that promotes bio software packaging and provides Bioconductor packaging information in Japanese. BioPackathon also organizes BioC Asia 2021 and has conducted survey to overcome language barriers.
The Software Carpentry Japanese Team is a community that localizes Carpentries teaching materials in Japanese.
Bioconductor is creating Carpentries-style teaching materials, and it is important for Bioconductor that Carpentries' activities become active in Japan.
The Bioconductor Community Advisory Board has a board member in Japan, and is planning to improve accessibility from Japan to Bioconductor in line with the CZI EOSS project.
In this BOF, the above will be explained in slides and the future prospects will be introduced.

## Day4

### (15:00~) Yohei Kumagai (熊谷洋平): Introduction of academic recruiting platform tayo (求人プラットフォーム tayo の紹介)
**This talk will be conducted in Japanese.**
**本トークは日本語で行われます。**

Compared to employment in the private sector, there is a lack of information about entering graduate school, and this has become a bottleneck in the flow of human resources in academia.
This presentation will introduce [tayo](https://tayo.jp/)’s efforts to revitalize the flow of human resources in academia and create a world where a diverse people can aim to become scientists.

民間に比べて大学院への進学に関する情報が不足しており、これが学界の人材の流れのボトルネックになっています。
このプレゼンテーションでは、学界における人材の流れを活性化し、多様な人々が科学者になることを目指すことができる世界を創造するための [tayo](https://tayo.jp/) の取り組みを紹介します。
 
### (15:30~) Zuguang Gu: "spiralize: an R Package for Visualizing Data on Spirals"
 
The spiral layout has two major advantages for data visualization. First, it is able to visualize data with long axes, which greatly improves the resolution of visualization. Second, it is efficient for time series data to reveal periodic patterns. Here we present the R package spiralize that provides a general solution for visualizing data on spirals. spiralize implements numerous graphics functions so that self-defined high-level graphics can be easily implemented by users. The spiralize package is available at https://CRAN.R-project.org/package=spiralize.
