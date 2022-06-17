# Projection Analysis
Projection of n dimensional data through a selected plane.

## Background
This analysis provides a framework to take n dimensional data and pass it through a user defined two or three dimensional plane. By passing the data through a selected plane, we can understand where most of the variation in the data is, based on a selected frame of reference (i.e., our defined plane). The purpose of this is much like a principal component analysis. However, this framework allows one to orient the data in any way they wish, instead of just the first two principle components (as in a PCA analysis). 

This particular analysis was applied to a high dimensional phenotpyic data set of soil microbiomes. The purpose was to understand how much impact an invasive microbe has on the phenotypic profile of a soil microbial community. Hence, we projected the data through a projection matrix, whose boundaries were defined by the phenotypic profile of an uninvaded soil microbiome and the phenotpyic profile of the invasive microbes. In between this boundary, we assessed if the phenotypic profile of an invaded soil microbiome was closer to the boundary of the uninvaded soil microbiome or that of the invader. Hence, we could thus quantify the impact an invasive microbe has on the phenotype of an invaded soil microbiome. 

The analysis was performed in mathematica, and it was a collaboration between Sander van Doorn and myself. A more in depth explanation and the full result of this analysis can be found in the paper: https://www.nature.com/articles/s41396-017-0003-y. 

![projection_analysis_fig](https://user-images.githubusercontent.com/56315077/174263522-f6885b06-94a2-4945-b0de-5a7e8cb1c955.png)
