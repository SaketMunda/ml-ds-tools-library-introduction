# Machine Learning & Data Science Tools & Libraries

## Introduction

This repo helps to setup [development environment](https://github.com/SaketMunda/ml-ds-tools-library-introduction/blob/master/README.md#environment-setup) for data science and machine learning projects and also the introduction of some tools and libraries like,

- Jupyter Notebook
- Pandas
- Numpy
- Matplotlib
- Scikit Learn

## Environment Setup

  Download [MINIConda](https://docs.conda.io/en/latest/miniconda.html)

  Create a folder say, *sample_project*
  
  Setup development environment and install required tools using conda, 
  `conda create —prefix ./env pandas numpy matplotlib scikit-learn`
  
  Activate conda,
  `conda activate environment_directory`
  
  List out the active environment using `conda env list`
 
  Use `conda install [package/tool_name]`, if any tool is missed for the installation in the above step

  Now your environment is setup, open Jupyter Notebook as the browser editor for writing python code
 
  Terminate the process from terminal when done
 
  Then deactivate conda, `conda deactivate`
