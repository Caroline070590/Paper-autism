# Code Repository for:
**"Diagnosis of autism spectrum disorder based on functional brain networks and machine learning"**  
Published in *Scientific Reports*  
[DOI:(https://doi.org/10.1038/s41598-023-34650-6)](https://www.nature.com/articles/s41598-023-34650-6)

## Overview
This repository contains the code used in our study exploring the classification of autism spectrum disorder (ASD) based on functional brain networks using machine learning.

## Input Data
The input data consists of functional connectivity matrices derived from resting-state fMRI BOLD signals. These matrices are used to compute complex network features and train machine learning models.

### 📁 Where can I find the matrices?
The input matrices can be accessed through the **Supplementary Material** of the published article:  
🔗 [Supplementary Info on Nature.com](https://www.nature.com/articles/s41598-023-08072-3#Sec24)

> ⚠️ Note: Only anonymized or pre-processed matrices are included due to data privacy restrictions.

## Repository Structure
- `Calculate-all-measures.ipynb`: Computes complex network measures from the connectivity matrices.
- `Machine-Learning-parallelized.ipynb`: Performs classification of ASD using various machine learning algorithms.
- `measures.py`: Contains helper functions used across the notebooks to extract network metrics.

## Citation
If you use this code, please cite our paper:
Alves, Caroline L., et al. "Diagnosis of autism spectrum disorder based on functional brain networks and machine learning." Scientific reports 13.1 (2023): 8072.
