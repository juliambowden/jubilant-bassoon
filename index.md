---

layout: page
title: CoGAPS
subtitle: (Coordinated Gene Association in Pattern Sets)
hero_image: /jubilant-bassoon/images/hero.jpg
<!-- hero_height: is-fullwidth -->
hero_darken: true
show_sidebar: false
hero_link: https://github.com/FertigLab/CoGAPS
hero_link_text: GitHub Repository

---

<!-- <img src="/images/CoGAPSLogoSmall.png" alt="CoGAPS Logo" style="float:left;width:150px;height:166px;" style= "margin:right;5px;"> -->

## Introduction

[![Bioc](https://bioconductor.org/images/logo_bioconductor.gif)](https://bioconductor.org/packages/CoGAPS)
[![downloads](https://bioconductor.org/shields/downloads/release/CoGAPS.svg)](http://bioconductor.org/packages/stats/bioc/CoGAPS/)
[![Build Status](https://travis-ci.org/FertigLab/CoGAPS.svg?branch=master)](https://travis-ci.org/FertigLab/CoGAPS)

Coordinated Gene Association in Pattern Sets (CoGAPS) is a technique for latent space learning in gene expression data. CoGAPS is a member of the Nonnegative Matrix Factorization (NMF) class of algorithms. NMFs factorize a data matrix into two related matrices containing gene weights, the Amplitude (A) matrix, and sample weights, the Pattern (P) Matrix. Each column of A or row of P defines a feature and together this set of features defines the latent space among genes and samples, respectively. In NMF, the values of the elements in the A and P matrices are constrained to be greater than or equal to zero. This constraint simultaneously reflects the non-negative nature of gene expression data and enforces the additive nature of the resulting feature dimensions, generating solutions that are biologically intuitive to interpret (Seung and Lee (1999)).

CoGAPS has two extensions that allow it to scale up to large data sets, Genome-Wide CoGAPS (GWCoGAPS) and Single-Cell CoGAPS (scCOGAPS). This package presents a unified R interface for all three methods, with a parallel, efficient underlying implementation in C++.

## Citing CoGAPS

If you use the CoGAPS package for your analysis, please cite Fertig et al. (2010)

If you use the gene set statistic, please cite Ochs et al. (2009)
