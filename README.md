# TS-academy-3-
User segmentation on Instagram visit and spending data using K-Means clustering. Includes EDA, Elbow Method, and Silhouette Score evaluation on 2,600 users.

# Instagram Visit & Spending Behaviour

## Overview
This project applies unsupervised machine learning to segment users
based on their Instagram visit score and spending rank. Using K-Means
clustering, users are grouped into distinct behavioural segments to
uncover meaningful patterns in social media engagement and spending
habits.

---

## Dataset
- **Rows:** 2,600 users
- **Features:** 3 columns

| Column | Description | Type |
|---|---|---|
| `User ID` | Unique identifier for each user | int64 |
| `Instagram visit score` | Score representing frequency of Instagram visits | int64 |
| `Spending_rank (0 to 100)` | Spending rank of user (0 = lowest, 100 = highest) | float64 |

---

## Objectives
- Explore and understand the distribution of Instagram visit scores
  and spending ranks
- Apply K-Means clustering to segment users into distinct groups
- Determine the optimal number of clusters using the Elbow Method
  and Silhouette Score
- Interpret and label each cluster based on behavioural patterns

---

## Tech Stack
| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation |
| NumPy | Numerical computing |
| Matplotlib / Seaborn | Data visualization |
| Scikit-learn | K-Means clustering & Silhouette Score |
| Jupyter Notebook | Development environment |

---

## Analysis Workflow

### 1. Exploratory Data Analysis (EDA)
- Exploring the data
- Checking for missing values and outliers

### 2. Feature Preparation
- Feature scaling / normalisation
- Selecting clustering features

### 3. K-Means Clustering
- Elbow Method to find optimal number of clusters (k)
- Fitting K-Means model
- Assigning cluster labels to users

### 4. Model Evaluation
- Silhouette Score to measure cluster quality
- Visualising clusters

### 5. Cluster Interpretation
- Analysing characteristics of each cluster
- Labelling segments (e.g. High Visitors / High Spenders)

---

## Results
| Metric | Value |
|---|---|
| Optimal K (clusters) | 4 |
| Silhouette Score | 4 |

---

## 👥 Customer Segments
| Cluster | Instagram Visit Score | Spending Rank | Label |
|---|---|---|---|
| Cluster 0 | 63 | 24.050708 |  High Visitors, Low Spenders |
| Cluster 2 | 82 | 86.890232 |  High Visitors, High Spenders|
| Cluster 3 | 14 | 31.492397	| Low Visitors, High Spenders |

---

fy distinct
  user engagement and spending patterns
