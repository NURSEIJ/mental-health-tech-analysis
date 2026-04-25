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

---

## 🛠️ Technologies Used

- **Python 3.12**
- **pandas** - Data manipulation
- **scikit-learn** - K-Means clustering, PCA, preprocessing
- **matplotlib & seaborn** - Visualizations
- **Jupyter Notebook** - Interactive analysis

---

## 📊 Visualizations

| Visualization | Purpose |
|---------------|---------|
| Elbow Method | Determine optimal number of clusters |
| Silhouette Score | Validate cluster quality |
| PCA Scatter Plot | 2D visualization of clusters |
| t-SNE Projection | Alternative cluster visualization |
| Bar Chart | Cluster size distribution |

---

## 💡 HR Recommendations

### Cluster 0 (Anxious but Aware)
- Implement anonymous mental health support channels
- Provide manager training on compassionate communication
- Create peer support groups

### Cluster 1 (Supported and Open)
- Leverage as mental health ambassadors
- Feature in company communications
- Gather feedback on current programs

### Cluster 2 (Uncertain and Uninformed)
- Launch company-wide mental health awareness campaign
- Clarify existing mental health policies and benefits
- Host all-hands meetings with mental health focus

---

## 📚 References

Key academic sources supporting this analysis:

- Anttila et al. (2025) - Cluster analysis in occupational health
- Sharma et al. (2025) - ML for employee mental health analysis
- Ramesh Naidu et al. (2025) - OSMI dataset ML framework
- Patel et al. (2025) - Digital transformation and IT mental health

*Full bibliography available in the report.*

---

## 👩‍💻 Author

**Ijeoma Eze**  
Applied Artificial Intelligence Student  
https://github.com/NURSEIJ/mental-health-tech-analysis

---



## 🙏 Acknowledgments

- Open Sourcing Mental Illness (OSMI) for providing the survey data
- IU University for the Unsupervised Machine Learning course
- Course instructors for guidance on this case study
