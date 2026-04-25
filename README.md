# Mental Health in Technology: Unsupervised Machine Learning Analysis

## 📊 Project Overview

This project analyzes the **OSMI Mental Health in Tech Survey 2016** dataset using unsupervised machine learning techniques to identify distinct employee segments based on their attitudes toward mental health in the workplace.

### Key Objectives

- Process high-dimensional, messy survey data with missing values
- Apply K-Means clustering to identify employee segments
- Create visualizations (PCA, t-SNE) to interpret clusters
- Provide targeted HR recommendations for each segment

### Dataset

- **Source:** Open Sourcing Mental Illness (OSMI) 2016 Survey
- **Size:** 1,433 responses × 63 questions
- **Population:** Technology industry employees

---

## 🔧 Methodology

### Data Preprocessing
- Removed columns with >50% missing values
- Standardized gender responses (70+ unique entries → 6 categories)
- Selected 12 relevant features for clustering
- Applied Label Encoding and Standard Scaling

### Clustering
- **Algorithm:** K-Means
- **Optimal clusters:** 3 (interpretability) / 7 (statistical optimal)
- **Visualization:** PCA and t-SNE

---

## 📈 Key Findings

### Three Employee Clusters Identified

| Cluster | Size | Characteristics |
|---------|------|-----------------|
| **Cluster 0** | 442 (30.8%) | "Anxious but Aware" - High fear, high help-seeking, low comfort |
| **Cluster 1** | 353 (24.6%) | "Supported and Open" - High comfort, low fear, no observed stigma |
| **Cluster 2** | 638 (44.5%) | "Uncertain and Uninformed" - Low awareness, ambivalent attitudes |

---

## 📁 Repository Structure
