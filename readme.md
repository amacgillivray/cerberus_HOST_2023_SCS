# CERBERUS - IEEE HOST 2023
[DEMO LINK](https://youtu.be/JxXAU5iE-uA)

This repository replicates (including images) the environment we used to train and run our model for the 2023 IEEE HOST SCS competition.

There are two important python notebooks:
 - build_model.ipynb
 - **run_model.ipynb** - USE THIS TO RUN OUR MODEL

## build_model.ipynb
This file contains the code we used to train and test our original model.

## run_model.ipynb
Merely open the notebook and run.

This notebook will run the model on:

 - the training data
 - the test data
 - the holdout data

For the test and training data, the accuracy and confusion matrix will be printed.

For the holdout data, a list of predictions and their associated IDs will be printed.
This should match the outputs shown in `sample_submission.csv`. 

## Submission Information

 - The report is provided in this folder at report.pdf
 - Code is provided at https://github.com/amacgillivray/cerberus_HOST_2023_SCS
 - Code without data is also available in "code_nodata" in this directory
 - Sample submission is in "sample_submission.csv"
 - The demo is provided at https://youtu.be/JxXAU5iE-uA
 - The presentation is provided in this folder, as both a powerpoint and PDF: 
   - presentation.pptx
   - presentation.pdf
