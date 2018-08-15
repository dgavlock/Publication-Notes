# Notes on Predicting Fluorescent Labels in Unlabeled Images

# Summary

**In Silico Labeling (ISL)** can reliably predict some fluorescent labels from transmitted-light images of unlabeled fixed or live biological samples

-----------

# Introduction

* Staining has limitations on its reliability and value for many reasons, some are listed:
	* Specificity varies
	* labeling is time-consuming
	* Specialized reagents are expensive
	* Labeling often needs to be done under fixed conditions
	* Commonly non-specific signaling (Ab Cross-Reactivity)
	* Significant Batch-to-Batch variability
	* Limited Time-Window for Imaging

* The idea here is that unlabeled images can identify more information than is readily apparent from the cells via ML--Deep Learning techniques were employed (Deep Neural Networks)
	* These techniques were limited by having to know cell locations, *this is what the paper set out to find out*

* ***Sought to determine if computers can find and predict features in unlabeled images taht normally only become visible with labeling***

* Designed and trained a DNN  to predict:
	* Location
	* Texture on nuclei
	* Cell Health
	* Cell Type
	* Subcellular Structure

* The model could also do transfer learning (Can learn ***New Labels***)


---------


# Results

## Training and Testing Datasets for Supervised Machine Learning

1. Created a Dataset of function mapping from set of z-stacks of transmitted-light images to a set of all fluorescent labels in the training set (Max Projection Images were used)

## Developing Predictive Algorithms with Machine Learning

1. Used Supervised ML to determine if predictive relationships could be found between transmitted-light and fluorescence images of the same cells

2. Preprocessing was done to acommodate constraints imposed by the samples, data acquisition, and the network (Normalized all pixel values using STAR Methods)

3. The DNN performed a non-linear pixel-wise classification

To be continued

