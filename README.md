# 🛍️ Customer Segmentation Using Clustering

This project focuses on segmenting customers based on their **spending behavior**, **age**, **income**, and **preferences** using clustering algorithms like **K-Means** and **Hierarchical Clustering**. The outcome is a system that helps businesses understand different groups of customers to better tailor their marketing strategies.

---

## 📊 Dataset

- **Source:** [Mall Customer Segmentation Dataset on Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Attributes:**
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🧠 Approach

1. **Exploratory Data Analysis (EDA):**
   - Examined distributions of age, gender, income, and spending scores.
   - Identified clusters visually using scatter plots and pair plots.
   - Observed a strong diversity in spending patterns and income groups.

2. **Clustering Techniques Applied:**
   - **K-Means Clustering:**
     - Elbow method suggested **5 optimal clusters**.
     - Segmented customers into groups based on annual income and spending score.
   - **Hierarchical Clustering:**
     - Dendrogram revealed an optimal number of **5 clusters**.
     - Applied Agglomerative Clustering for hierarchical grouping.

3. **Visualization:**
   - Used scatter plots, pair plots, and seaborn styling to visualize segments.
   - Cluster behavior was clearly distinguished:
     - High income + low spenders
     - Low income + high spenders
     - High income + high spenders
     - Low income + low spenders
     - Average/Moderate clusters

---

## 📈 Results

### K-Means Clustering:

- Number of Clusters: **5**
- Segments successfully distinguish:
  - High-spending and low-income groups
  - High-income but low-spending groups
  - Balanced average-income & spending segments

### Hierarchical Clustering:

- Confirmed the presence of **5 natural clusters** via dendrogram.
- Produced comparable segmentation as K-Means but with hierarchical relationships.

---

## ✅ Key Insights

- **Young customers** tend to spend more regardless of income.
- **Middle-aged customers** with high income tend to spend less, potentially more financially conservative.
- **Gender** shows minor influence compared to **income and spending score**.

---

## 📦 Dependencies

Make sure to have the following Python libraries installed:

- Python 3.x
- [pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [scikit-learn](https://scikit-learn.org/)
- [scipy](https://www.scipy.org/)

