# Clustering Analysis on the Adult Dataset

This repository contains the code, data, and report for a clustering analysis project on the Adult dataset from the UCI Machine Learning Repository. The objective is to discover interesting patterns in the data using clustering techniques.

---

## Project Overview

The Adult dataset, originally developed for classification tasks, has been repurposed for clustering in this project. The analysis includes data preprocessing, performing exploratory data analysis, applying clustering methods, and interpreting the results.

---

## Repository Structure

### 1. `code/`

Contains the R script for the analysis:

-   `clustering.r`: Performs data preprocessing, clustering, and outputs cluster characteristics.

### 2. `data/`

Contains the dataset used for the analysis:

-   `adult.data`: The Adult dataset from the UCI Machine Learning Repository.

### 3. `output/`

Contains the analysis results:

-   `cluster_characteristics.csv`: Describes the mean values of each cluster and their labels.

### 4. `report/`

Contains the detailed project report:

-   `Report.docx`: Documents the step-by-step implementation, results, and discussion.

---

## How to Use

1. **Prerequisites:**

    - Install R and required libraries (e.g., `ggplot2`, `cluster`, `dplyr`).
    - Download the repository.

2. **Steps to Run:**

    - Place `adult.data` in the `data/` folder.
    - Run `clustering.r` in R.
    - Review the output in `output/cluster_characteristics.csv`.

3. **Project Report:**
    - Refer to `Report.docx` for the complete analysis and findings.

---

## Highlights

-   **Clustering Techniques:** Explores multiple methods for pattern discovery such as K-means Clustering, Hierarchical Clustering, Partitioning Around Medoids (PAM), Density-Based Spatial Clustering of Applications with Noise (DBSCAN), and Fuzzy C-Means clustering methods.
-   **Cluster Analysis:** Provides labeled clusters based on mean characteristics.
-   **Comprehensive Documentation:** Detailed report and output files for replication and evaluation.

---

## Dataset Information

The Adult dataset can be accessed from the UCI Machine Learning Repository: [Adult Dataset](https://archive.ics.uci.edu/dataset/2/adult).

---

## Contact

For any questions or feedback, please use the repository’s issue tracker.
