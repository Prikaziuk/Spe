# Spe

The work is based on Speuledrbos EC site data: NL-Spe.

Flux partitioning - separation of the net ecosystem exchage (NEE) to gross primary productivity (GPP) and ecosystem respiration (Reco).

This code was created for educational puproses to show:
- how the eddy covariance data can be prepared for flux partitioning (tibble and tsibble R packages):
  1. Merging of csv-files
  2. Reading and resampling radiation data
- flux partitioning itself with the [REddyProc R package](https://github.com/bgctw/REddyProc) [(Wutzler et al., 2018)](https://doi.org/10.5194/bg-15-5015-2018).
  1. This part repeats the use-case https://cran.r-project.org/web/packages/REddyProc/vignettes/useCase.html
