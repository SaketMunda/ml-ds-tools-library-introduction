# Machine Learning & Data Science Tools & Libraries

## Contents

- [Introduction](https://github.com/SaketMunda/ml-ds-tools-library-introduction/blob/master/README.md#introduction)
- [Environment Setup](https://github.com/SaketMunda/ml-ds-tools-library-introduction/blob/master/README.md#environment-setup)
- [Share Conda Environment](https://github.com/SaketMunda/ml-ds-tools-library-introduction/blob/master/README.md#share-conda-environment)
- [Pandas](https://github.com/SaketMunda/ml-ds-tools-library-introduction/blob/master/README.md#pandas)
- [NumPy](https://github.com/SaketMunda/ml-ds-tools-library-introduction/blob/master/README.md#numpy)
- [Matplotlib](https://github.com/SaketMunda/ml-ds-tools-library-introduction/blob/master/README.md#matplotlib)
- [Scikit-Learn](https://github.com/SaketMunda/ml-ds-tools-library-introduction/blob/master/README.md#scikit-learn)
- [Workbooks](https://github.com/SaketMunda/ml-ds-tools-library-introduction/blob/master/README.md#workbooks)
- [Resources](https://github.com/SaketMunda/ml-ds-tools-library-introduction/blob/master/README.md#resources)
- [Special Thanks To !](https://github.com/SaketMunda/ml-ds-tools-library-introduction/blob/master/README.md#special-thanks-to)

## Introduction

This repo helps to setup [development environment](https://github.com/SaketMunda/ml-ds-tools-library-introduction/blob/master/README.md#environment-setup) for data science and machine learning projects and also the introduction of some tools and libraries like,

- [x] [Jupyter Notebook](https://jupyter.org/)
- [x] [Pandas](https://pandas.pydata.org/)
- [x] [Numpy](https://numpy.org/)
- [x] [Matplotlib](https://matplotlib.org/)
- [x] [Scikit Learn](https://scikit-learn.org/stable/)

## Environment Setup

  
  > Brief About the Workspace
  
  **[Anaconda](https://www.anaconda.com/)**
  - platform for datascience packages to run or use in your program
  - It comes with lots of tools
  - It's like a complete hardware store
  - software distribution tool
    
  **[MINIConda](https://docs.conda.io/en/latest/miniconda.html)**
  - also the same as Anaconda, but comes with less tools yet useful    
  - It's like a workbench
  - software distribution tool
  
  **[Conda](https://docs.conda.io/en/latest/)**
  - is like a personal assitant to setup your projects, tools, packages and environments
  - this is a package manager
  - used to setup your environment using DS and ML tools like matplotlib, pandas etc.
    
  **[Jupyter Notebook](https://jupyter.org/)**
  - Workspace to access tools within environment for your datascience projects.
  
    
  > So for light weight setup, we will install **MINIConda** and then install the tools and packages when required.

  
  Download [MINIConda](https://docs.conda.io/en/latest/miniconda.html)

  Create a folder say, *sample_project*
  
  Setup development environment and install required tools using conda, 
  - `conda create —prefix ./env pandas numpy matplotlib scikit-learn`
  
  Activate conda,
  - `conda activate environment_directory`
  
  List out the active environment using `conda env list`
 
  Use `conda install [package/tool_name]`, if any tool is missed for the installation in the above step

  Now your environment is setup, open Jupyter Notebook as the browser editor for writing python code
 
  Terminate the process from terminal when done
 
  Then deactivate conda, `conda deactivate`
  
## Share Conda Environment
  
   If you want to share your Conda Env with other devs then you can do in couple of ways,
   1. Sharing the whole project folder, which could be expensive as lots of MBs of data in form of packages and files
   2. Share a .yml file of your conda environment 
    
   For 2nd option, we need .yml file of your conda environment, for this we will export the environment as YAML file called environment.yml

   **Command**:

   ***TO Export***
   - `conda env export —prefix [env_folder_path] > [file_name.yml]`

   ***TO Create Env using .yml file***
   - `conda env create —file [file_name.yml] —name [environment_name]`

## Pandas

**A Data Analysis tool/library**

> What

It is used to explore data, analyse data, manipulate data when we use python for data analysis

> Why

- simple to use
- integrated with many other data science and machine learning python tools
- helps you get your data ready for ML

> [Topics covered in this introduction](https://github.com/SaketMunda/ml-ds-tools-library-introduction/blob/master/introduction-to-pandas.ipynb)

- Most useful functions
- Pandas datatypes
- Importing & Exporting data
- Describing data
- Viewing & selecting data
- Manipulating data

## NumPy

> What

**Numeric Python** - It has multidimensional arrays and numbers.

It has similar to Python lists, then why NumPy and must use tool in Machine Learning problems.

> Why

- behind the scenes optimization, written in C
- computation is faster in terms of using GPUs & other hardwares
- can be really useful as machines only understand `0` & `1` binary, so NumPy converts everything in numbers like Images to array of numbers.
- Vectorization via broadcasting (avoiding loops)
- backbone of other scientific packages like pandas

> [Topics covered in this introduction](https://github.com/SaketMunda/ml-ds-tools-library-introduction/blob/master/introduction-to-numpy.ipynb)

- Most useful functions
- NumPy datatypes & attributes
- Creating arrays
- Viewing arrays & matrices
- Manipulating & Comparing arrays
- Sorting arrays
- Use Cases

## Matplotlib

**Visualization of Data**

> What

- Python plotting library
- It allow to turn the data into charts & graphs, figures

> Why

- Built on NumPy arrays (& python)
- Integrates directly with Pandas
- Can create basic or advance plots
- Simple to use interface(once you get the foundation, *the basic*)

> [Topics covered in this introduction](https://github.com/SaketMunda/ml-ds-tools-library-introduction/blob/master/introduction-to-matplotlib.ipynb)

- matplotlib Workflow
- Importing matplotlib & the 2 ways of plotting
- Plotting data from NumPy arrays
- Customizing plots
- Saving & Sharing plots

## Scikit-Learn

**Python ML Library**, aka *sklearn*

> What

- If we have data, Scikit learn helps us to build machine learning models to make predictions or learn patterns within that data & then make predictions.
- Also implements tools to help us evaluate those predictions whether good or bad ?

> Why 

- Built on NumPy & Matplotlib (and Python)
- Has many in-built ML models.
- Methods to evaluate your ML models
- Very well-designed APIs

> [Topics covered in this introduction](https://github.com/SaketMunda/ml-ds-tools-library-introduction/blob/master/introduction-to-scikit-learn.ipynb)

- A scikit-learn workflow
- Getting the data ready
- Choosing a right estimator/model/algorithm for our problems
- Fitting a model to the data (learning patterns)
- Making predictions with a model (using patterns)
- Evaluating model predictions
- Improving model predictions
- Saving & Loading models

## Workbooks

Here are some practice workbooks for different libraries,

- [x] [Python Exercise](https://www.w3schools.com/python/exercise.asp?filename=exercise_syntax1)
- [x] [Pandas Workbook by Daniel Bourke](https://github.com/mrdbourke/zero-to-mastery-ml/blob/master/section-2-data-science-and-ml-tools/pandas-exercises.ipynb)
- [x] [NumPy Workbook by Daniel Bourke](https://github.com/mrdbourke/zero-to-mastery-ml/blob/master/section-2-data-science-and-ml-tools/numpy-exercises.ipynb)
- [ ] [Regex Exercise](https://regexone.com/lesson/introduction_abcs)
- [x] [Matplotlib Workbook by Daniel Bourke](https://github.com/mrdbourke/zero-to-mastery-ml/blob/master/section-2-data-science-and-ml-tools/matplotlib-exercises.ipynb)
- [ ] [Scikit-Learn Workbook by Daniel Bourke](https://github.com/mrdbourke/zero-to-mastery-ml/blob/master/section-2-data-science-and-ml-tools/scikit-learn-exercises.ipynb)

## Resources
- [Zero To Mastery Machine Learning & Data Science Program](https://zerotomastery.io/courses/machine-learning-and-data-science-bootcamp/)
- [A Visual Intro to NumPy and Data Represenation](https://jalammar.github.io/visual-numpy/)
- [The Basics of NumPy Arrays](https://jakevdp.github.io/PythonDataScienceHandbook/02.02-the-basics-of-numpy-arrays.html)
- [Feature Scaling with scikit-learn By Ben Alex Keen](https://benalexkeen.com/feature-scaling-with-scikit-learn/)
- [Feature Scaling : Why it's required By Rahul Saini](https://rahul-saini.medium.com/feature-scaling-why-it-is-required-8a93df1af310)
- [Decision Trees & Explanation of Random Forest By Will Koehrsen](https://willkoehrsen.github.io/machine%20learning/tutorial/an-implementation-and-explanation-of-the-random-forest-in-python/)
- [Beyond Accuracy : Precision and Recall By Will Koehrsen](https://towardsdatascience.com/beyond-accuracy-precision-and-recall-3da06bea9f6c)
- [ROC and AUC, Clearly Explained By StatQuest](https://www.youtube.com/watch?v=4jRBRDbJemM)

## Special Thanks To!
- [Daniel Bourke](https://twitter.com/mrdbourke)
- [Andrei Neagoie](https://twitter.com/andreineagoie)

   
