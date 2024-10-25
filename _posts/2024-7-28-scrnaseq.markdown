---
layout: post
title:  "Differential Expression Analysis of Single-Cell RNA-Seq Pancreatic Endocrine Cell Data"
date:   2024-7-28 00:00:00 -0700
categories: jekyll update
---

**Problem Statement**

Type 2 diabetes mellitus (T2DM) is a common and debilitating condition, wherein the pancreas produces insufficient quantities of insulin and cells become resistant to the presence of insulin. Insulin is a hormone which allows cells to take in glucose, so the effect of type 2 diabetes is that afflicted individuals have difficulty in processing sugar. The causes behind type 2 diabetes are complex, among them being genetic conditions: there is therefore a need to identify the differences in genetics between healthy and diabetic individuals.

Statistical analysis of RNA-Seq data—data which describes the presence and quantity of RNA in a cell, which in turn identifies which genes are being expressed (presence) and at what rates (quantity)—can be used to identify differential expression of genes between different types of cells. The purpose of this analysis is to identify which genes are differentially expressed to a statistically significant degree between healthy and T2DM patients.

**Summary**

This is a project I performed as a part of my Computational Data Analysis class, which delved into the statistical background of many common machine learning tasks including dimensionality reduction, clustering, expectation maximization, maximum likelihood estimation, and so on. The requirement of this project was to implement the statistical methods we learned in class for an analytical problem of our choosing; the decision to pursue a bioinformatics task was my own.

Data was sourced from the recount3 public RNA-seq data repository.

<div align="center">
<img src="/Portfolio/assets/images/isomap.png" width="350" height="auto"> 
<text>ISOMAP representation of data after variance stabilizing transformation.</text>
</div>

Duties I performed as a part of implementing this analysis include:

- Surveying current literature on scRNA-seq data analysis and differential expression analysis to identify industry best practices for this type of data.

- Implemented R bioinformatics libraries including Bioconductor, DESeq2, etc. for statistical analysis to build pipeline for cleaning, transforming, and analyzing initial raw counts data.

- Utilized biology background and scientific literature to analyze the biological ramifications of differentially expressed genes.

- Drafted report of results in scientific journal format using LaTeX.

- Effecively communicated complex biology domain knowledge to colleagues with data science backgrounds.

<div align="center">
<img src="/Portfolio/assets/images/disp_estimates.png" width="350" height="auto"> 
<text>Visualization of initial dispersion estimates, the fitted trend, and the final dispersion estimate.</text>
</div>

Most importantly, this project was a fantastic learning experience!

<div align="center">
<img src="/Portfolio/assets/images/dif_genes.png" width="500" height="auto"> 
<text>Differentially expressed genes clustered based on correlation compared with control group.</text>
</div>

The report and source code cannot be shown publicly in order to comply with academic integrity policies. If you would like to see them, send me an email at danielpatrickwebster@gmail.com.

