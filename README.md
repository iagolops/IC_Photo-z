# Photo-z analyses for the TPz algorithm

The objective of this project is to build a sample for TPz algorithm and analyze the results. 

## Manual for notebooks
The main folder is /IC_Photo-z/Iago. Here we have some files:

* Flexzboost.ipynb
Notebook to execute FlexzBoost and analyse results.

* Controlled_sample.ipynb
Notebook to build and analyze a sample with VIPERS and GAMA catalogs. 

* Sanchez_run_TPz.ipynb
Notebook to replicate the training sample from the paper (DOI: 10.1093/mnras/stu1836), analyse results and calculate weights.

* DR2-Spec_Querys.ipynb
Notebook to build a sample using spectroscopic data from LIneA server.

* Plots.ipynb
Notebook for plotting results; you can combine more than one result and compare.

## Manual for samples folder
The path to the folder is: /IC_Photo-z/Iago/samples.


This folder contains all the training, validation and input files for ML algorithms.

Example: training.VVDS_VIPERS contains the training file built using VVDS and VIPERS catalog.


The folder /IC_Photo-z/Iago/results contains all results after running TPz.

REGRESSION: 0
CLASSIFICATION: 1
More than 1: tests

Example: results.GAMA_VIPERS_VVDS.1.mlz contains results from TPz using classification. 

## Manual for other files and folders

* IC_Photo-z/MLZ 
Folder with the TPz algorithm

* IC/Photo-z/Files png
Contain all the images saved from notebooks

* /IC_Photo-z/Iago/samples/phot_sample_weighting_{catalog}
Photometric data downloaded to weighting. Each data has the cuts used in spectroscopic associated.

* /IC_Photo-z/Iago/Sanchez_data
Contains the data used to try to replicate Sanchez's paper results.

