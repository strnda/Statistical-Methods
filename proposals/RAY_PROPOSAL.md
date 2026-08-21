# Paper Proposal Submission

## 1. Student Information
* **Name:** Ray Kettaren
* **PhD Study Program:** Water resource and environmental modeling
* **Dissertation Topic Summary:** Impact of anthropogenic climate
  warming to hydrological extreme event attribution

## 2. Paper Details
* **Paper Title:** Streamflow drought: implication of drought definitions and its application for drought forecasting
* **Authors:** Samuel J. Sutanto and Henny A. J. Van Lanen
* **Year & Journal:** 2021, Hydrology and Earth System Sciences
* **DOI / Link:** https://doi.org/10.5194/hess-25-3991-2021


## 3. Methodological Focus
* **Core Statistical/Algorithmic Methods to Implement:** 
Threshold-level drought identification using fixed and variable Q80 thresholds derived from the flow-duration curve, including 30‑day centered moving-average smoothing of monthly thresholds to obtain daily values.

Event extraction via theory of runs: detection of start/end dates when flow crosses below/above the threshold, followed by pooling/filtering of minor events using a 30‑day moving average on daily discharge.

Drought-characteristic computation: event duration, deficit volume (sum of threshold − flow over event days), and aggregation to annual or full-period statistics (counts, mean duration, total/mean deficit, most common start month).

Standardized Streamflow Index (SSI‑1) module: month-of-year gamma distribution fitting (method of moments), probability-to-normal transformation, and drought definition at SSI < −0.84 (≈ Q80).

## 4. Technical Implementation Strategy
* **Target Language:** Python
* **Target Output:** Python C
* **Key Dependencies planned:** Numpy, pandas, scipy
* **Validation Strategy:** Generate artificial daily discharge series
  with known threshold crossings and drought events to verify that: 
Fixed and variable thresholds are computed correctly.
Event start/end dates, durations, and deficit volumes match hand-calculated expectations.
SSI‑1 transformation yields approximately standard normal scores under
  the assumed gamma model.)
Event counts, mean durations, and deficit volumes against values reported in the paper’s figures/tables for similar climate regions.
Seasonal patterns of drought onset (e.g., most common start month) with the paper’s regional results.
