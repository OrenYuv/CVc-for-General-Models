# CVc-for-General-Models
This repository includes the codes corresponding to Chapter 4 of my Ph.D. dissertation, entitled "Cross-validation for correlated data in general models for regression and classification, with applications to Deep Learning".

Access to the CelebA dataset (available at https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) is required in order to generate Figure 6.

The datasets used in Figure 7 can be found within the directory labeled 'DNN model on AirBNB data'.

To create Figure 6, first execute the 'Smile Detection' code file and save the output. Subsequently, execute 'Plot Figure 6,' ensuring the data importation call points to the correct path. The 'Smile Detection' code file can be run multiple times with the 'SampSize1' variable set to 20 for each run to prevent extended runtimes, and the resulting data can be aggregated.


To create Figure 7, first execute the 'Hot-water Detection' code file and save the output. Subsequently, execute 'Plot Figure 7,' ensuring the data importation call points to the correct path. The 'Hot-water Detection' code file can be run multiple times with the 'SampSize1' variable set to 40 for each run to prevent extended runtimes, and the resulting data can be aggregated.


