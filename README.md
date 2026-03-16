# PCA and Cluster Analysis

Multivariate statistical analysis project using principal component analysis and clustering to reduce dimensionality, identify structure in the data, and interpret meaningful group differences.

## Overview
This project applies principal component analysis (PCA) and clustering techniques to explore patterns in multivariate data. The analysis was designed to simplify a higher-dimensional dataset into a smaller number of interpretable components, then use clustering methods to identify distinct groupings within the observations.

## Project Objective
The goal of this project was to:
- reduce dimensionality while retaining the most informative variation in the data
- interpret the strongest underlying component patterns
- compare clustering approaches for grouping similar observations
- evaluate whether the final clusters produced meaningful and interpretable segments

## Methods
The analysis included:
- **Principal Component Analysis (PCA)**
- **Scree plot / component selection**
- **Principal component interpretation**
- **Hierarchical clustering**
- **K-means clustering**
- **Silhouette-based cluster evaluation**

## Analytical Approach
The workflow followed a typical multivariate analysis process:
1. standardize and examine the multivariate feature space
2. use PCA to identify the most informative lower-dimensional structure
3. interpret the retained principal components
4. apply clustering methods to the transformed data
5. compare candidate cluster solutions
6. select and interpret the most meaningful grouping structure

## Key Outcomes
- PCA was used to reduce the original feature space into a smaller number of interpretable dimensions.
- Principal component selection was supported using scree-plot style evaluation and variance-based reasoning.
- Both hierarchical clustering and k-means were used to compare grouping behavior across the reduced feature space.
- Cluster quality was evaluated using silhouette-based reasoning to support the final segmentation choice.
- The final analysis focused not just on statistical grouping, but on whether the resulting clusters were practically interpretable.

## Why This Project Matters
This project demonstrates how multivariate methods can be used to move from complex raw variables to a simpler, more interpretable structure. It highlights a common real-world analytics workflow:
- simplify the data
- identify latent patterns
- segment observations
- interpret the resulting groups for decision-making

## Repository Contents
- `reports/pca-cluster-analysis-report.pdf` — final report

## Skills Demonstrated
- principal component analysis
- clustering
- dimensionality reduction
- multivariate statistical analysis
- pattern discovery
- segment interpretation
- statistical reasoning
- analytical communication

## Notes
This repository presents a graduate-level multivariate analysis project in portfolio format. It emphasizes methodology, interpretation, and analytical reasoning rather than software engineering or application deployment.
