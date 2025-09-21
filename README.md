---
title: "Reconstructing the Origin and Demographic Expansion of the TP53 p.R337H Founder Variant in Brazil"
output: pdf_document
date: "2025-09-21"
---

# Reconstructing the Origin and Demographic Expansion of the TP53 p.R337H Founder Variant in Brazil

This repository contains the R code and data necessary to reproduce the results presented in the article:

**"Reconstructing the Origin and Demographic Expansion of the TP53 p.R337H Founder Variant in Brazil"**  
Emilia Modolo Pinto¹*, João Carlos Degraf Muzzi²*, José Andres Yunes³⁴*, Bonald C. Figueiredo², Raul C. Ribeiro⁵, Gerard P. Zambetti¹  
(*co-first authors)

---

## Overview

This study aims to estimate the time of origin and model the demographic expansion of the TP53 p.R337H founder variant in Southern Brazil. Using historical census data, exponential growth models, and Monte Carlo simulations, we reconstruct possible scenarios for the introduction and spread of the variant over time.

The analysis is fully implemented in **R** and includes:

- Data curation and preprocessing of Brazilian census population figures.
- Exponential population growth modeling.
- Monte Carlo simulations for founder carrier counts.
- Visualization of predicted trajectories and historical comparisons.

---

## Dependencies

The code was developed using **R version ≥ 4.1.0** and the following packages:

- `tidyverse`
- `cowplot`
- `scales`
- `sf`
- `geobr`

To install all dependencies:

```r
install.packages(c("tidyverse", "cowplot",  "sf", "scales", "geobr"))
```                  

## How to Run

To replicate all results and generate the figures:
  Open the file founder_model.Rmd in RStudio or any RMarkdown-compatible IDE.
  Knit the document to PDF format.
  Output figures will be saved in the current working directory.  

## Citation

If you use this code or data, please cite:

Pinto EM, Muzzi J, Yunes JA, Figueiredo BC, Ribeiro RC, Zambetti GP.
Reconstructing the Origin and Demographic Expansion of the TP53 p.R337H Founder Variant in Brazil.
Cancer Epidemiology, Biomarkers & Prevention. [In press].

## Contact

For questions regarding the code or analysis, please contact:

Dr. João Muzzi: joao.muzzi@gmail.com / jmuzzi@quantumds.tech
Dr. Emilia Pinto: emilia.pinto@stjude.org

