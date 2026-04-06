# Zero-Shot Model Merging with Coordinate-wise Median

Code for my course project on zero-shot model merging.

## Overview
This project studies whether coordinate-wise median can improve zero-shot model merging compared with naive mean.

## Methods
- Naive Mean
- Coordinate-wise Median
- TIES

## Settings
- Mistral 7B
- BERT
- Mild heterogeneity (`N=3`)
- Extreme heterogeneity (`N=7`)

## Files
- `Project_merge_clean.ipynb`
- `Project_7B_Limit_Test_clean.ipynb`

## Result
Coordinate-wise median is more robust than naive mean under mild heterogeneity, but under extreme heterogeneity, aggregation alone becomes insufficient.

## Author
Enze Zhao
