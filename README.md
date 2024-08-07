# Sparse and Integrative Principal Component Analysis for Multiview Data (SIPCA)
Lin Xiao, Luo Xiao (2023). arxiv:  https://arxiv.org/abs/2301.06718
This repository provide code to implement the 'Sparse and Integrative Principal Component Analysis (SIPCA)' method in the above manuscript. The folder 'SIPCA_functions' contains all utility functions for method implementation and simulation data generation. The 'SIPCA_application' folder has two code demos to apply SIPCA to estimate sparse eigenvectors in the scenarios where the noise levels are either homoskedastic or heteroskedastic across different data views. A code sample to apply SIPCA to TCGA data (https://www.cancer.gov/ccg/research/genome-sequencing/tcga) is also provided. Feel free to contact veraxiao93@gmail.com if you have any questions regarding the code.

R Packages that need to be installed before running the code: 'Rcpp', 'RcppEigen', 'MASS', 'RSpectra', 'RMTstat', 'RcppArmadillo'.
