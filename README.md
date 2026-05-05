# Democracy Clustering Analysis
Unsupervised machine learning project analyzing 167 countries 
using the Economist Democracy Index.

## What This Project Does
Applies K-Means and Hierarchical Clustering to group countries 
based on five democratic indicators, then compares algorithmic 
clusters against official regime classifications.

## Dataset
Economist Intelligence Unit — Democracy Index
167 countries × 5 features:
- Electoral Process & Pluralism
- Functioning of Government
- Political Participation
- Political Culture
- Civil Liberties

## Methods Used
- StandardScaler for feature normalization
- K-Means Clustering (k=4, determined via Elbow Method)
- Hierarchical Clustering (Ward + Complete linkage)
- Density plots per cluster for distribution analysis

## Key Findings
- K-Means (k=4) aligned closely with the 4 official regime types
- Ward linkage produced more balanced clusters than Complete linkage
- Political Participation showed highest variance across clusters
- Civil Liberties was the strongest separator between Full 
  Democracies and Authoritarian regimes

## Tech Stack
Python | Pandas | Scikit-learn | Matplotlib | Jupyter Notebook

## Author
Iman Othman
MS Data Analytics Engineering — Northwestern University
[LinkedIn Profile URL]
https://www.linkedin.com/in/iman-o-675585377?utm_source=share_via&utm_content=profile&utm_medium=member_ios
