# Paper Proposal Submission

## 1\. Student Information

* **Name:** Karel Pátek
* **PhD Study Program:** Environmental Earth Sciences, Environmental Modelling
* **Dissertation Topic Summary:** The role of forest transpiration in the hydrological cycle.

## 2\. Paper Details

* **Paper Title:** Spatial autocorrelation and the selection of simultaneous autoregressive models
* **Authors:** W. Daniel Kissling, Gudrun Carl
* **Year \& Journal:** 2007, Global Ecology and Biogeography
* **DOI / Link:** https://doi.org/10.1111/j.1466-8238.2007.00334.x

## 3\. Methodological Focus

* **Core Statistical/Algorithmic Methods to Implement:**

  * Simultaneous autoregressive models

&#x20;       -> spatial error model (SARerr)



## 4\. Technical Implementation Strategy

* **Target Language:** \[ ] R
* **Target Output:** R Package
* **Key Dependencies planned:** spdep, ncf
* **Validation Strategy:** Using data provided by authors. The dataset ("error data" dataset) as well as the procedure description is provided by authors. The correlogram created by the spatial error model will then be compared with the graph in the article (with the Fig. 2 a) that shows the correlogram the authors obtained by this method on this dataset).

