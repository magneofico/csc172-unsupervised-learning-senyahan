# CSC172 – Unsupervised Learning Activities

## Student Information  
**Name:** Kristoffer Neo Senyahan  
**GitHub:** https://github.com/magneofico  
**Date:** 2025-11-23  

---

## Overview

This repository contains my completed activities for CSC172 focusing on **unsupervised learning**, specifically **K-Means clustering** and **Association Rule Mining (Apriori Algorithm)**. The notebook demonstrates data preprocessing, visualization, algorithm implementation, and interpretation of results.

---

## What is Unsupervised Learning?

Unsupervised learning is a type of machine learning where the model is given **unlabeled data** and must discover underlying patterns or structures on its own. Unlike supervised learning, there are no predefined outputs. Instead, the system learns relationships within the data, making it useful for:

- Identifying natural groups
- Discovering hidden patterns
- Finding associations or frequent behaviors
- Reducing dimensionality

Two major unsupervised techniques covered in this activity are **Clustering** and **Association Rule Mining**.

---

## Clustering (K-Means)

**Clustering** is the process of grouping similar data points together based on their features.  
In this activity, I used **K-Means**, one of the most commonly used clustering algorithms.

### How K-Means Works:
1. Choose a value for **k** (the number of clusters).
2. Randomly initialize **k centroids**.
3. Assign each data point to the nearest centroid.
4. Recalculate the centroids based on assigned points.
5. Repeat until cluster assignments stabilize.

### Why Clustering Matters:
Clustering helps reveal **natural groupings** in data without needing labels.  
In the provided dataset (annual income and spending score), clustering can show:

- High-income high-spending customers  
- Low-income low-spending customers  
- Moderate consumer groups  

It is valuable in customer segmentation, market analysis, and behavior profiling.

---

## Association Rule Mining (Apriori Algorithm)

**Association Rule Mining** identifies patterns of items that frequently occur together in transactional data.  
A common example is "market basket analysis"—understanding what items customers buy together.

### Key Metrics:
- **Support:** How often the itemset appears in the dataset  
- **Confidence:** How often the rule is true (if A happens, how often does B also happen?)  
- **Lift:** How much more likely the items occur together compared to chance (lift > 1 means a meaningful association)

### Example Rule:
> (Notebook) → (Pen)  
> Students who buy a Notebook also buy a Pen 85.7% of the time.

### Why It Matters:
Association rules help identify:

- Product bundles  
- Complementary items  
- Behavioral patterns  
- Purchasing tendencies  

Businesses use this for recommendation systems, cross-selling strategies, and inventory planning.

---

## Summary of Activities

1. **K-Means Clustering:**  
   - Loaded customer dataset  
   - Visualized features  
   - Applied clustering  
   - Identified meaningful customer segments  
   - Explained cluster patterns  

2. **Association Rule Mining:**  
   - Created a student transaction dataset  
   - Applied one-hot encoding  
   - Used Apriori to find frequent itemsets  
   - Generated association rules with lift  
   - Visualized rules  
   - Interpreted the strongest patterns  

---

## Repository Contents

- `Unsupervised_Learning.ipynb` – Completed notebook with all code, outputs, and written interpretations.
- `README.md` – Explanation of the activities and concepts.

