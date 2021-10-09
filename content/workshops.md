+++
title = "Workshops"
description = "Workshops"
+++

**The workshop will be held from 4pm to 5pm Japan time (UTC+09:00) from November 1st to 4th.**

## Japanese Workshops

### (Day1) 山本 博之 Hiroyuki Yamamoto: "Rを用いたメタボロームデータ解析: Metabolome data analysis using R"

BioconductorパッケージXCMSを用いた、メタボロミクスにおける質量分析データ処理の手順を簡単に紹介する。次に、Rパッケージloadingsを用いた多変量解析の手順を紹介する。loadingsパッケージは、メタボロームデータを可視化するだけでなく、主成分負荷量やPartial last squares 負荷量とそれらの統計的仮説検定を用いて、有意な代謝物を選択することが出来る。

I will briefly introduce the procedure for mass spectrometry data processing in metabolomics using the R Bioconductor package “XCMS”. And, I will also introduce the procedure for multivariate analysis using R package “loadings”. The “loadings” package can not only visualize metabolome data, but also select significant metabolites using Principal component loadings, Partial least squares loadings and their statistical hypothesis testing.

### (Day2) 久米 慧嗣 Satoshi Kume: "Rにおけるバイオ画像解析入門: Introduction to Bioimaging Analysis in R"

このワークショップでは、BioconductorパッケージであるEBImageを使って、Rでの画像処理・画像解析の基本的な方法を扱う。次に、BioImageDbsパッケージを用いて、ExperimentHubからの画像データの取得を行う。さらに、rMiWパッケージが提供する、Deep learningモデルの１つであるU-NETモデルを用いて、教師有り画像セグメンテーション（領域分割）を学び。このワークショップは、Orchestra環境にて実施する。

This workshop covers basic methods of the image processing and image analysis in R using the Bioconductor package "EBImage" and the Orchestra platform. In addition, the image dataset is obtained from ExperimentHub using the "BioImageDbs" package. Using this dataset, we perform a supervised image segmentation using the U-NET model, one of deep learning models, provided by the rMiW package.

### (Day3) 露崎 弘毅 Koki Tsuyuzaki: "細胞間相互作用解析ワークショップ: Cell-cell Interaction Analysis Workshop"

このワークショップでは、1細胞RNA-Seqデータに含まれるリガンド-受容体の共発現を根拠とした、細胞間相互作用（CCI）の解析を紹介する。また、CCIを網羅的に検出・可視化するためのR/BioconductorパッケージscTensorの使い方を説明する。

In this workshop, I will introduce the analysis of cell-cell interaction (CCI) on the basis of ligand-receptor co-expression in single-cell RNA-Seq data. I will also explain how to use the R/Bioconductor package scTensor for comprehensive detection and visualization of CCIs.

### (Day4) 西田 孝三 Kozo Nishida: "RCy3 を用いた Cytoscape の自動化: Cytoscape automation with RCy3"

RCy3は、RからCytoscapeを操作するBioconductorパッケージです。このワークショップでは、[RCy3というBioconductorパッケージ](https://bioconductor.org/packages/release/bioc/html/RCy3.html)と[オーケストラプラットフォーム](http://app.orchestra.cancerdatasci.org/1) を使用して、プログラマチックなワークフローやパイプラインへのCytoscapeの統合について学習します。

ネットワーク分析におけるCytoscapeの機能の簡単なレビューに続いて、これらを実用的なスクリプト可能なユースケースに変換する方法を学習します。ワークショップの大部分は、RからCytoscapeにアクセスして制御し、[腫瘍の発現量](https://cytoscape.org/cytoscape-tutorials/presentations/modules/RCy3_ExampleData/data/TCGA_OV_RNAseq_expression.txt)のネットワーク分析を実行する方法の実践的なデモンストレーションです。Cytoscapeの操作は手作業ではなく、すべてRで行われるため、そのワークフローは作業効率が良く、再現性も高いものとなっています。

このワークショップを修了すると、次のことができるようになります。
1. Cytoscapeに対するコマンドプログラムによる制御
2. Cytoscapeのバイオインフォマティクスのパイプラインへの統合
3. さまざまなツールとリソースを1つの R Markdownにまとめること

[RCy3](https://bioconductor.org/packages/release/bioc/html/RCy3.html) is a Bioconductor package that operates [Cytoscape](https://cytoscape.org/) from R. In this workshop, you will learn about the integration of Cytoscape into programmatic workflows and pipelines using RCy3 Bioconductor package and [the Orchestra platform](http://app.orchestra.cancerdatasci.org/1).

Following a brief review of the capabilities of Cytoscape in network analysis, you’ll learn how to translate these into scriptable use cases for practical applications. The bulk of the workshop will be a demonstration of how to access and control Cytoscape from RCy3 to perform a network analysis of [tumor expression](https://cytoscape.org/cytoscape-tutorials/presentations/modules/RCy3_ExampleData/data/TCGA_OV_RNAseq_expression.txt). Since all Cytoscape operations are done in R, not manually, it is efficient and reproducible.

By the end of this workshop you will be able to:
1. Command programmatic control over Cytoscape
2. Integrate Cytoscape into your bioinformatics pipelines
3. Pull together various tools and resources into a single R Markdown

---

## Mandarin Workshops

### (Day1) Jinjin Chen: "Gene-set Analysis Workshop"

Differential expression analysis is a standard and popular statistical framework in biological research. Differentially expressed genes can be identified by comparing different conditions or treatments. Biologists are often interested in the biological implications of these differentially expressed genes, since they could reveal the latent functions and networks in biological system. Many gene functions have been well-annotated in some knowledgebases, such as GO and KEGG. By mapping and identifying the annotated functions of special gene-sets, we can understand broader impacts of functional analysis.

This workshop will focus on performing gene-set enrichment analysis of transcriptomic data and visualizing the results of enrichment analysis. It will begin with loading data from ExperimentHub using the emtdata and msigdb R/Bioconductor packages. It will demonstrate functional analysis of transcriptomic data using the molecular signatures database (through the msigdb R/Bioconductor package) and a gene-set enrichment method, singscore. Finally, we will perform a graph-based approach to visualize, summarize and interpret results of gene-set enrichment analysis, demonstrating how higher order biological themes can be identified in data using the vissE package.

The workshop will be organized into two broad sections:

1. Molecular phenotyping of individual samples
2. Identifying and visualizing higher-order phenotypes

### (Day2) 孙建强 Jianqiang Sun: "Introduction to image recognition with deep learning"

卷积神经网络（Convolutional neural network; CNN）是用于图像识别的深度神经网络架构之一。 使用传统的机器学习方法来识别图像中的物体需要手动指定物体的特征，如颜色、大小、长宽比等。 相比之下，CNN 可以通过学习大量的图像，自动提取该特征。 因此，使用 CNN 建立一个图像识别模型，只需要收集大量的图像，而无需开发新的算法来提取特征。 如今，这种简单易行的方法在许多研究领域备受欢迎。在本次研讨会上，我们将学习如何使用为 R 提供的 torch 软件包来构建 CNN 模型进行图像识别。

Convolutional neural network (CNN) is one of the deep neural network architectures used for image recognition. In contrast to the traditional machine learning methods that require humans to manually specify the features of objects such as color, size, aspect ratio, and so on, CNNs can automatically extract that feature by learning a large number of images.  Thus, building an image recognition model using CNN requires only collecting a large number of images without developing new algorithms to extract features. Today, this simple and easy method is popular in many research areas. In this workshop, we will learn how to use an R package named torch to build CNN models for image recognition.

### (Day3) 孙建强 Jianqiang Sun: "Prediction of CRISPR guide RNA activity with deep learning"

深度学习在计算机视觉以及自然言语处理等诸多领域取得重大成果，其技术现已被应用在包括生命科学在内的其它领域。深度学习主要通过构建深度神经网络来解决传统机器学习算法难以解决的问题。在诸多种深度学习的网络结构中，卷积神经网络（Convolutional neural network; CNN）以及循环神经网络（Recurrent neural network; RNN）最为人们熟知。其中，卷积神经网络在目标识别及目标检测等计算机视觉领域表现出色；循环神经网络则是在时间序列数据处理以及自然言语处理方面表现出色。在本次研习会上，我们考虑到众多 Bioconductor 用户熟悉于基因组序列分析，因此我们将讲解循环神经网络的基本算法以及如何使用 R 构建循环神经网络的方法。

Deep learning has proven to be one of the state-of-the-art tools in object recognition and natural language processing, and has been applied to many fields. Deep learning refers to the use of multiple layers of neural networks which is one of the traditional machine learning algorithms. Deep neural networks can solve problems that are difficult to solve with conventional machine learning algorithms. At present, various architectures of deep neural networks have been published, especially convolutional neural networks (CNN) and recurrent neural networks (RNN) are well known. The former is known to be excellent in computer visions such as object recognition and object detection, while the latter, RNN, is known to be excellent in time-series data analysis and natural language processing. Considering many Bioconductor users are familiar with genome sequence analysis, in this workshop, we will focus on RNN, and introduce the fundamental algorithm of RNN and procedures to build RNN models using R.

### (Day4) Lang Chau: "Visualization and exploration of MSAs and associated data with ggmsa"

The stacked alignment graphic that represents all individual sequences as rows and homologous residue positions as columns is used almost universally in the visualization of multiple sequence alignment (MSA). We present the R package ggmsa to extend MSA visualization method via integrating stacked MSAs and associated data. Sequence-related data sets such as secondary structures, genes locus, or phenotype are allowed to combining with MSA for exploring the sequence-structure-function relationship. And we developed and integrated multiple alignment visualization methods such as nucleotide difference plots, nucleotide similarity plots, and sequence bundles to exploring multifaceted sequence features from multiple perspectives. The ggmsa package is available at https://github.com/YuLab-SMU/ggmsa.

The workshop will be organized into three broad sections:

Visualization of MSAs and annotations via Grammar of Graphics
Integration of stacked MSAs plot and associated data.
Exploration of sequence features via different sequence visualization methods

---

## English Workshops

### (Day1) Kozo Nishida: "Cytoscape automation with RCy3"

[RCy3](https://bioconductor.org/packages/release/bioc/html/RCy3.html) is a Bioconductor package that operates [Cytoscape](https://cytoscape.org/) from R. In this workshop, you will learn about the integration of Cytoscape into programmatic workflows and pipelines using RCy3 Bioconductor package and [the Orchestra platform](http://app.orchestra.cancerdatasci.org/1).

Following a brief review of the capabilities of Cytoscape in network analysis, you’ll learn how to translate these into scriptable use cases for practical applications. The bulk of the workshop will be a demonstration of how to access and control Cytoscape from RCy3 to perform a network analysis of [tumor expression](https://cytoscape.org/cytoscape-tutorials/presentations/modules/RCy3_ExampleData/data/TCGA_OV_RNAseq_expression.txt). Since all Cytoscape operations are done in R, not manually, it is efficient and reproducible.

By the end of this workshop you will be able to:
1. Command programmatic control over Cytoscape
2. Integrate Cytoscape into your bioinformatics pipelines
3. Pull together various tools and resources into a single R Markdown

### (Day2) Aedin Culhane: "Dimension Reduction for Beginners: Hitchhiker’s Guide to Matrix Factorization and PCA"

This workshop will provide a beginner’s guide to matrix factorization, principal component analysis (PCA), the difference between singular value decomposition, different forms of PCA and fast PCA for single-cell data as well as correspondence analysis and decomposition of the Pearson Residuals. We will describe how to detect artifacts and select the optimal number of components. It will focus on SVD, PCA, COA applied toy datasets and single-cell data.

Principal component analysis (PCA) is a key step in many bioinformatics pipelines. In this interactive session we will take a deep dive into the various implementations of singular value decomposition (SVD) and principal component analysis (PCA) to clarify the relationship between these methods, and to demonstrate the equivalencies and contrasts between these methods. We will describe correspondence analysis (COA) and demonstrate how it differs from PCA. We will also discuss interpretation of outputs, as well as some common pitfalls and sources of confusion in utilizing these methods.

### (Day3) Federico Marini: "GeneTonic: enjoying the interpretation of your RNA-seq data analysis"

RNA-seq transcriptome analysis workflows often generate the essential information (data and results) among a variety of different tabular files and formats, e.g. raw and normalized expression values, results of differential gene expression analysis, or functional enrichment analysis. If this information is fragmented over single different files, the interpretation of the results can be hampered.

We present the GeneTonic package (https://bioconductor.org/packages/GeneTonic/), containing a Shiny application which provides an efficient and interactive possibility to combine the results of RNA-seq analysis. GeneTonic assists the identification of relevant functional patterns, as well as their contextualization in the data and results at hand, with interactivity (to make the analysis simple and accessible) and reproducibility (via RMarkdown reports) to simplify the integration of all components. With GeneTonic, users can generate a variety of visualizations, including bird’s eye perspective summaries (with interactive bipartite gene-geneset graphs or enrichment maps) as well as detailed information and visualizations of individual genes and gene-sets. These can be further inspected via drill-down actions that display additional content in specific elements of the user interface.

In this workshop, we will provide an overview of the functionality of GeneTonic, and demonstrate its usage in classical RNA-seq workflows, showcasing how it is possible to integrate our package with the single components of typical differential expression scenarios, with the goal of streamlining the interpretation and in-depth exploration for this widely used application.

### (Day4) Laurent Gatto: "Single-cell proteomics data analysis using QFeatures and scp"

Mass spectrometry (MS)-based single-cell proteomics (SCP) is an emerging field that requires a dedicated computational environment. QFeatures along with its extension scp allow for standardized analysis of SCP data. The workshop will start by introducing the QFeatures class and its functions to perform generic proteomics data analysis. We will then
move to SCP and present how scp extends QFeatures to single-cell applications. The remainder of the workshop will be a hands-on session where attendees will be guided through the reproduction of a real-life analysis of published SCP data. Along the reproduction exercise, we will point out to current challenges that still need to be tackled computationally. This workshop is meant for inexperienced users that want to learn how to perform current state-of-the-art analysis of SCP data as well as experienced developers interested in contributing to an emerging and exciting single-cell technology.

This workshop is provided as two vignettes. The first vignette provides a general introduction to the QFeatures class in the general context of MS-based proteomics data manipulation. The second vignette focuses on single-cell application and introduces the scp package as an extension of QFeatures. This second vignette also provides exercises that give the attendee the opportunity to apply the learned concepts to reproduce a published analysis on a subset of a real data set.
