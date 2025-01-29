# CCD0 and Hipstr results

This directory contains the point estimates we obtained using the following estimators. No burn-in was used.

## CCD0-full

We used the full CCD0 algorithm as published as [version 1.0.2](https://github.com/CompEvol/CCD/releases/tag/v1.0.2) of the CCD0 package. The source code can be found in [this repo](https://github.com/CompEvol/CCD/blob/results/src/ccd/model/CCD0.java).

| Dataset         | log(MCC) |
| --------------- | -------- |
| EBOV-516        | -923.66  |
| EBOV-1610       | -2886.25 |
| EBOV-Sim        | -1767.58 |
| SARS-CoV-2-3959 | -8416.94 |

## CCD0-no-expansion

These results are obtained with the CCD0 parameterization on the CCD1 graph with no expansion (not adding any unobserved clade splits). The source code can be found in [this repo](https://github.com/CompEvol/CCD/blob/results/src/ccd/model/CCD0.java).

| Dataset          | log(MCC)  |
| ---------------- | --------- |
| EBOV-516         | -950.08   |
| EBOV-1610        | -3039.60  |
| EBOV-Sim         | -1786.64  |
| SARS-CoV-2-3959  | -8745.53  |
| SARS-CoV-2-15616 | -51399.93 |

## Hipstr

These results are obtained with the Hipstr algorithm from TreeAnnotator X 10.5.0.

| Dataset          | log(MCC)  |
| ---------------- | --------- |
| EBOV-516         | −950.08   |
| EBOV-1610        | -3039.60  |
| EBOV-Sim         | -1786.64  |
| SARS-CoV-2-3959  | -8630.85  |
| SARS-CoV-2-15616 | -51352.61 |
