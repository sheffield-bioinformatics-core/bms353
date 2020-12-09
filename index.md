---
title: "BMS353 Bioinformatics for Biomedical Science"
author: "Module Coordinator Mark Dunning"
output: 
  html_document: 
    toc: yes
    toc_float: yes
    css: stylesheets/styles.css
editor_options: 
  chunk_output_type: inline
---

<img src="images/logo-sm.png" style="position:absolute;top:40px;right:10px;" width="200" />

# About 

## Pre-material

We will assume you have a basic familiarity with the R language and Rstudio and are reasonably confident in performing the following tasks:-

- Creating new RStudio projects and markdown files
- Importing spreadsheets into R
- Filtering, arranging and selecting with `dplyr`
- Plotting using `ggplot2`

You should also be familiar with the overall workflow of RNA-seq data.

Sufficient preparation may be obtained by following [BMS397](https://sbc.shef.ac.uk/bms397)

# Aims

This module is aimed at biology students with little or no knowledge of programming and statistics. It has the following objectives:

- making students aware of effects of experimental design in the subsequent data analysis;
- having a good understanding of technologies and methods for Bioinformatics;
- Introduce basic coding in R and exercise use of workflow and pipelines on real case study.

BMS353 will use a multidisciplinary approach integrated with programming tools and cloud environment to introduce students to statistical concepts underpinning advanced data analysis and methods for high-throughput data analysis. Theoretical concepts and detailed examples will be introduced to provide the students with key steps to perform experimental design in data collection, data analysis and results validation. The pipeline will be then used to analyse real case studies.

The course will present state-of-the art research in computational biology and enable students to critically assess statistical methods and enhance innovative thinking in data analysis.

## Contact

email: [m.j.dunning@sheffield.ac.uk](m.j.dunning@sheffield.ac.uk)

# Course Data

Please use the link below to download the example RNA-seq dataset for the course

- [Download here](https://sbc.shef.ac.uk/bms353/bms353.zip)

# Week 1 - R for Reproducible Biological Analysis

## Learning outcomes

- Overview of the course
- Recap how R and RStudio can facilitate reproducible research
- Tour of resources available through Bioconductor 
- Installation of packages required for the remainder of the course

## Pre-materials

- [A non reproducible workflow](https://youtu.be/s3JldKoA0zw) - 2 minutes
- [Bioconductor introduction](https://youtu.be/dg6NvmMVQ3I) - 5 minutes
- [A tour of the Bioconductor website](https://www.youtube.com/watch?v=HgbnSMiqlOg) - 5 minutes
- [The importance of reproducibility in high-throughput Biology](https://youtu.be/7gYIs7uYbMo) - 37 minutes


## Materials
- [html](week1.html)
- [Solutions to in-class exercise - Rmd](solutions/week1.Rmd)
- [Solutions to in-class exercise - HTML](solutions/week1.nb.html)


# Week 2 - Introduction to analysis high-throughput biological data

## Learning outcomes

- Defining the keys steps in the analysis of high-throughput biological data
    + quality assessment
    + normalisation
    + differential expression
- Outline the fundamentals of statistical testing for biological data
- Demonstrate how familiar R functions can be applied to biolgical data

## Pre-materials

- [Gene Expression Analysis and DNA microarray Assays](https://youtu.be/Hv5flUOsE0s) - 8 minutes
- [Quantile Normalisation for high-throughput Biology](https://youtu.be/ecjN6Xpv6SE) - 5 minutes
- [Statistics for Genomics](https://youtu.be/3huF0DwxCtU) - 30 minutes
- [Multiple Testing Correction](https://youtu.be/K8LQSvtjcEo) - 18 minutes


## Materials

- [html](week2.nb.html)
- [markdown](week2.Rmd)
- [solutions - markdown](solutions/week2.Rmd)
- [solutions - HTML](solutions/week2.nb.html)


# Week 3 - Importing RNA-seq counts into R and quality assessment

## Learning outcomes

- Exploring count data and importing these data into R
- Normalisation strategies for RNA-seq counts
- Quality Assessment of counts
- Identifying outliers, batch effects and sample mix-ups

## Pre-Materials

- [A gentle introduction to RNA-seq](https://youtu.be/tlf6wYJrwKY) - 18 minutes
- [RNA-seq count normalisation explained](https://youtu.be/TTUrtCY2k-w) - 10 minutes
- [Principal Components Analysis](https://www.youtube.com/watch?v=0Jp4gsfOLMs) - 9 minutes



## Materials


- [html](week3.nb.html)
- [markdown](week3.Rmd)
- [solutions - Rmd](solutions/week3.Rmd)
- [solutions - HTML](solutions/week3.nb.html)

# Week 4 - Differential Expression for RNA-seq

## Learning outcomes

- Which statistical tests are appropriate for RNA-seq data
- Using the DESeq2 package to detect differential expression
- Using a venn diagram to compare gene lists

## Pre-materials


- [Differential expression analysis](https://youtu.be/5tGCBW3_0IA) - 26 minutes

## Materials

- [html](week4.nb.html)
- [markdown](week4.Rmd)
- [solutions - Rmd](solutions/week4.Rmd)
- [solutions - HTML](solutions/week4.nb.html)


# Week 5 - Visualisation methods for RNA-seq data

## Learning outcomes

- Using annotation databases to map between gene identifers
- Construction and interpretation of common visualisations
    + scatter plots
    + volcano plots
    + MA-plots 
    + heatmaps
- Customisation of plots

## Pre-materials


- [Drawing and Interpreting Heatmaps](https://youtu.be/oMtDyOn2TCc) - 16 minutes
- [Useful plots and bad plots](https://youtu.be/46-t2jOYsyY) - 17 minutes


## Materials

- [html](week5.nb.html)
- [markdown](week5.Rmd)

# Week 6 - Pathways and further downstream analysis

## Learning outcomes

- Introduction to assessment
- Using annotation packages to query pathways
- Methodology behind gene set testing and enrichment analysis

## Pre-Materials

- [Introduction to Functional Gene Analysis](https://youtu.be/clb0bh3zFSM) - 12 minutes
- [Fisher's Exact test](https://youtu.be/udyAvvaMjfM) - 5 minutes
- [GSEA theory](https://youtu.be/bT00oJh2x_4) - 9 minutes

## Materials

<!--
- [html](week6.nb.html)
- [markdown](week6.Rmd)

-->