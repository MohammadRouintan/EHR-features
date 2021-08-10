# Predicting Stroke from Electronic Health Records

With the spirit of reproducible research, this repository contains all the codes required to produce the results in the manuscript: 

> details here.

Please cite the above paper if you intend to use whole/part of the code. This code is only for academic and research purposes.


## Code Organization
All codes are written in `R` and `python`. 

### Code 
The script to reproduce all the figures, tables in the paper are as follows:
+ `main.R`: main scripts in R
+ `boxplots_adding.py`: script to plot the boxplot of adding features
+ `boxplots_removing.py`: script to plot the boxplot of removing features
+ `PCA8-evaluation.R`: pca analysis stuffs
+ `top3-features.R`: Results obtained by considering top-3 features
+ `More details.ipynb`: Other experiments

### Results 
We also share the results obtained in our random downsampling experiments. The results obtained with the various benchmarking approaches is found in `my_results.csv`.