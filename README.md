# Customer Segmentation Using K-Means Clustering

This project implements a **K-Means Clustering Algorithm** to group customers of a retail store based on their purchase history. The goal is to segment customers into distinct clusters to better understand their purchasing behavior and tailor marketing strategies accordingly.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Process](#process)
- [Requirements](#requirements)
- [Installation](#installation)


## Project Overview

In this project, we use the K-Means clustering algorithm to analyze and segment customers of a retail store based on their historical purchasing data. By identifying different customer segments, the retail store can better target its marketing efforts, improve customer retention, and optimize its services.

## Dataset

The dataset consists of customer purchase history, including details like transaction amounts, frequency of purchases, and types of products purchased.

- **Dataset Source**: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python
- **Main Features**:
  - Customer ID
  - Total amount spent
  - Number of transactions
  - Product categories purchased
  - Frequency of purchases

## Process

### 1. Loading the Dataset
The dataset is loaded and structured for clustering analysis.

### 2. Data Exploration
Exploratory Data Analysis (EDA) is performed to understand the distribution of customer purchase data, identify patterns, and prepare the data for clustering.

### 3. Data Preprocessing
Data preprocessing steps include handling missing values, scaling the data, and selecting relevant features to ensure the dataset is suitable for clustering.

### 4. Building the K-Means Model
The K-Means algorithm is applied to the preprocessed data to segment customers into distinct clusters. The optimal number of clusters is determined using methods like the Elbow method.

### 5. Evaluating and Visualizing Clusters
The clusters are evaluated for cohesion and separation, and visualizations are created to represent the customer segments and their characteristics.

## Requirements

To run this project, you will need the following dependencies:

- Python 3.x
- Jupyter Notebook
- Libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

## Installation

Clone the repository and install the required dependencies.

```bash
git clone https://github.com/HassaanAi/customer-segmentation-kmeans.git
cd customer-segmentation-kmeans
