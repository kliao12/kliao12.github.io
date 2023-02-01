---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Bayesian Mixture of LD Score Regression Identifies Candidate Genes Driving Signals of Local Genetic Correlation (LGC)
* Synposis: This work aims to provide interpretability and identify potential actionable targets in signals of genetic correlation (shared genetic architecture across two traits). While existing approaches can estimate genetic correlation genome wide and in local regions, they do not provide which set of SNPs or genes drive that signal. Here, we use a bayesian mixture of LD score regressions framework to infer a latent class of "correlated" and "not correlated" SNPs/genes and test the effects of a given gene/group of variants on class membership. 
 
## A Novel Stacking Framework for Polygenic Risk Prediction in Admixed Individuals  
* Synopsis: This works aims to optimize polygenic risk prediction of complex traits in admixed individuals through leveraging GWAS summary statistics from the ancestral groups constituing ther admixture. In admixed African Americans, we developed a stacking framework where we stratify the genome into 5Mb non-overlapping windows. In each local window, a penalized regressions model incorporating population-specific effect sizes and local ancestry are fit in local 5Mb windows to create local predictions in each window, optimized for an individual's unique local ancestry. We then fit a second level penalized regression to aggregate local predictions genome wide into a single polygenic risk score.  

* [Poster presented at 2021 American Society of Human Genetics](https://github.com/kliao12/kliao12.github.io/blob/master/files/ASHG%202021%20Final.pptx)
  
## The Effect of Mutation Subtypes on the Allele Frequency Spectrum and Population Genetics Inference  
* Synopsis: This works considers the effect of local nucleotide context on the distribution of allele frequencies in a population. Mutation rate heterogeneity and biased gene conversion are two mechanisms that affect the AFS through sequence context. In addition, differences in the AFS among mutation subtypes results in drastically different AFS-based demographic inference methods which suggests current methods are biased by failing to account for local sequence context.
* [Oral Platform Talk presented at 2019 American Society of Human Genetics](https://github.com/kliao12/kliao12.github.io/blob/master/files/2019%20MSSISS%20Poster_Kevin%20Liao%20(2020_02_29%2001_13_00%20UTC).pdf)
  
## Comparing Similarity Measures over RNA-Seq Derived Gene Expression Profiles
*  Synopsis: This works compares 5 similarity measures (Euclidean distance, pearsons correlation, spearmans correlation, median absolute deviation, poisson similarity) and their effect on the performance of a K-Nearest Neighbors classifier. Samples were classified to specific tissue types based on their transcriptome. Ultimately, the commonly used pearsons correlation was found to provide the highest classification accuracy. 
* [Paper submitted to IBS-SRP Student Journal](https://github.com/kliao12/kliao12.github.io/blob/master/files/Kevin%20Liao%20Final%20Paper.pdf)
