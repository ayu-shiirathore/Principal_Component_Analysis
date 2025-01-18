# Principal Component Analysis (PCA) on Iris Dataset

This repository contains Python code for performing Principal Component Analysis (PCA) on the Iris dataset. The goal of this analysis is to reduce the dimensionality of the data while retaining as much variance as possible.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Dataset](#dataset)
- [PCA Implementation](#pca-implementation)
- [Steps](#steps)
- [Results](#results)
- [Conclusion](#conclusion)
- [License](#license)

## Introduction

Principal Component Analysis (PCA) is a technique used for dimensionality reduction while preserving as much variance as possible in the data. In this project, we apply PCA to the Iris dataset, which contains 150 samples of iris flowers from three different species, each having 4 features: sepal length, sepal width, petal length, and petal width.

By applying PCA, we can reduce the feature set from 4 dimensions to 2 (or fewer) while retaining the most important information about the dataset.

## Requirements

To run the PCA analysis, the following Python libraries are required:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install the required libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
