1. Student Information
Name: Sonjib Chakraborty
PhD Study Program: Water Resource and Environmental Modeling
Dissertation Topic Summary: Spatio-temporal patterns of links between mosquito-borne diseases and weather variability

2. Paper Details
Paper Title: Temporal relationship between environmental factors and the occurrence of dengue fever
Authors: Marco Aurelio Horta, Robson Bruniera, Fabricio Ker, Cristina Catita, and Aldo Pacheco Ferreira
Year & Journal: 2014, International Journal of Environmental Health Research
DOI / Link:https://www.tandfonline.com/doi/full/10.1080/09603123.2013.865713

3. Methodological Focus

Core Statistical/Algorithmic Methods to Implement: Distributed Lag Nonlinear Model (DLNM) to investigate the relationship between environmental factors, particularly temperature and rainfall, and dengue fever occurrence.

The implementation will focus on:
Nonlinear relationship between temperature/rainfall and dengue incidence.
Delayed effects of environmental factors over different time lags.
Estimation of relative risk associated with temperature and rainfall.
Identification of important lag periods associated with dengue occurrence.

4. Technical Implementation Strategy
Target Language: R
Target Output: R script implementing the DLNM analysis and producing plots of exposure-response and lag-response relationships.
Key Dependencies planned: dlnm, splines, ggplot2
Validation Strategy:
Use simulated data with known relationships and time lags to check whether the DLNM implementation works correctly.
Check whether the model can identify the expected delayed effects of temperature and rainfall.
Compare the estimated relative risks with the main results reported in the paper.
Compare the estimated lag patterns with the lag periods reported in the paper.
Compare the model plots with the relevant figures from the paper.
