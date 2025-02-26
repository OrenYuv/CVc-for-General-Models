# CVc-for-General-Models
This repository contains the code associated with the arXiv paper: "Cross Validation for Correlated Data in Regression and Classification Models, with Applications to Deep Learning" by Yuval and Rosset (2025), https://doi.org/10.48550/arXiv.2502.14808.

This paper is an expanded version of the published conference paper "Cross Validation for Correlated Data in Classification Models" authored by Oren Yuval and Saharon Rosset, which was recently accepted to the 28th International Conference on Artificial Intelligence and Statistics (2025).

It should be noted that the numbering of figures differs between the conference paper and this repository, which matches with the arXiv paper. Specifically, Figures 1 to 4 in the conference paper correspond to Figures 1, 3, 6, and 7 in this repository, respectively.



Access to the CelebA dataset (available at https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) is required in order to generate Figure 6.

The datasets used in Figure 7 can be found within the directory labeled 'DNN model on AirBNB data'.

To create Figure 6, first execute the 'Smile Detection' code file and save the output. Subsequently, execute 'Plot Figure 6,' ensuring the data importation call points to the correct path. The 'Smile Detection' code file can be run multiple times with the 'SampSize1' variable set to 20 for each run to prevent extended runtimes, and the resulting data can be aggregated.


To create Figure 7, first execute the 'Hot-water Detection' code file and save the output. Subsequently, execute 'Plot Figure 7,' ensuring the data importation call points to the correct path. The 'Hot-water Detection' code file can be run multiple times with the 'SampSize1' variable set to 40 for each run to prevent extended runtimes, and the resulting data can be aggregated.


