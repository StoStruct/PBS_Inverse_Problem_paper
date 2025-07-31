# Code and Data for "treating PBD as an inverse problem" paper
# 1. Overview
This repository contains the code and data needed to reproduce the main results of the paper
> 📌 **Please cite the following paper if you use this repository**  
>  
> Zaker Esteghamati, M., (2025).  
> *Toward using explainable data-driven surrogate models for treating performance-based seismic design as an inverse engineering problem*  
> *Proceedings of the Royal Society A DOI: 10.1098/rsta.2024.0050



## 2. Files in the repository
- **Data_RC.xlsx & Data_Steel.xlsx:** Includes two datasets of geometric, design, and seismic performance information for two RC and Steel moment-resisting frames datasets.
  The Original datasets were previously published and are cited in the above manuscript.

- **Main_Code_inverseProblem.ipynb:** In the main Jupyter notebook that reads the dataset files, trains a support vector machine, performs a Shapley explainability technique
  and produces all the plots for the paper until the Optimization Stage. The genetic optimization code for a sample 5-story building from RC dataset is provided at the end. 
  

## 3. How to run the code 
Users should run the main Jupyter Notebook file, where they have the option to choose either RC or Steel dataset. The optimization code for the RC building case study is provided. 
Users can modify this code to reproduce the optimization for the steel dataset by adjusting the design parameters according to the steel Dataset. 

## 3. Repository DOI
You can cite this repository as follows: 
Stochastic Structures Research Group. (2025). StoStruct/PBS_Inverse_Problem_paper: PBS_Inverse_Problem_v1.0 (papers). Zenodo. https://doi.org/10.5281/zenodo.16648424
