# Paper Proposal Submission

## 1. Student Information
* **Name:** Lauren Young
* **PhD Study Program:** Ecology
* **Dissertation Topic Summary:** Phylogeography of North American desert species of the genus Chenopodium.

## 2. Paper Details
* **Paper Title:** A global reference for human genetic variation
* **Authors:** 1000 Genomes Project Consortium; Adam Auton, Lisa D Brooks, Richard M Durbin, Erik P Garrison, Hyun Min Kang, Jan O Korbel, Jonathan L Marchini, Shane McCarthy, Gil A McVean, Gonçalo R Abecasis
* **Year & Journal:** 2015, Nature
* **DOI / Link:** [https://www.nature.com/articles/s42003-020-01169-9](https://doi.org/10.1038/nature15393)

## 3. Methodological Focus
* **Core Statistical/Algorithmic Methods to Implement:** 
  - PCA to summarize genetic variation and visualize population structure from genotype data in a VCF file

## 4. Technical Implementation Strategy
  - **Target Language:** [x] R  |  [ ] Python  |  [ ] C++
  - **Target Output:** R Package
  - **Key Dependencies planned:** vcfR, adegenet, testthat
  - **Validation Strategy:** A balanced subset of publicly available 1000 Genomes Project Phase 3 chromosome 22 data will be included with matching sample metadata. The package will be tested to confirm that it produces PCA scores and PC1 vs. PC2, PC1 vs. PC3, and PC2 vs. PC3 plots colored by a selected metadata column.
