# Welcome
The `data` folder contains the processed data used in the analyses.

The `figures` folder contains the figures in TIFF, PDF and PNG format.

The `results` folder contains the results as CSV files.

## Explanation of the R code

| Step | What it does |
|---|---|
| step00 | Folders and settings |
| step01 | Functions: RBO and its exact null distribution |
| step02 | Validation of the null distribution against Monte Carlo |
| step03 | Data download and loading: MAQC (GSE5350) and SEQC (GSE47774) |
| step04 | Calibration parameters and noise ceilings |
| step05 | Calibrated simulation of the estimator and the pairwise test |
| step06 | Real-data laboratory pairs and kappa curves |
| step07 | Global and laboratory-wise permutation tests |
| step08 | Batch diagnostic and leave-out tests |
| step09 | Figures and tables |
| step10 | Null grid check, global tests (B = 1999), k/p sensitivity, global test simulation, batch simulation, comparison with raw measures |
| step11 | IDR, leave-out tests (B = 999), extra simulation scenarios |
| step12 | Exact estimates over all splits, SEQC C vs D test, power simulation |
| step13 | Test on rho versus test on raw agreement |
| step14 | TIF copies of the figures |
| step15 | Processed data as gzip CSV |
