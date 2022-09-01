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
  
## Share Conda Environment
  
   If you want to share your Conda Env with other devs then you can do in couple of ways,
    - Sharing the whole project folder, which could be expensive as lots of MBs of data in form of packages and files
    - Share a .yml file of your conda environment 
    
   For 2nd option, we need .yml file of your conda environment, for this we will export the environment as YAML file called environment.yml

   **Command**:

   ***TO Export***
   `conda env export —prefix [env_folder_path] > [file_name.yml]`

   ***TO Create Env using .yml file***
   `conda env create —file [file_name.yml] —name [environment_name]`
