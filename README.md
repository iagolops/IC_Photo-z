# Photo-z analyses for the TPz algorithm

The objective of this project is to build a sample for TPz algorithm and analyze the results. 

## Manual for notebooks
The main folder is /TPz_notebooks/iago/ml_analyses. Here we have some files:

* DR2-Spec_Querys.ipynb
Notebook to build a sample using spectroscopic data from LIneA server.

* Plots.ipynb
Notebook for plotting results; you can combine more than one result and compare.

* Sanchez_run_TPz.ipynb
Notebook to replicate the training sample from the paper (DOI: 10.1093/mnras/stu1836), analyse results and calculate weights.

## Manual for samples folder
The path to the folder is: /TPz_notebooks/iago/ml_analyses/samples.


This folder contains all the training, validation and input files for TPz algorithm.

Example: training.VVDS_VIPERS contains the training file built using VVDS and VIPERS catalog.


The results folder contains all results after running TPz.

REGRESSION: 0
CLASSIFICATION: 1
More than 1: tests

Example: results.GAMA_VIPERS_VVDS.1.mlz contains results from TPz using classification. 

## Manual for other files and folders
* MLZ 
Folder with the TPz algorithm

* iago/Test_plots
Contains a replication of plots from TPz paper. 

* iago/ml_analyses/Sanchez_data
Contains the data used to try to replicate Sanchez's paper results.