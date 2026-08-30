# 📚 IBM Training & Learning

This repository contains my learning and practice notebooks from **IBM Machine Learning Training**, covering **Data Preprocessing, Missing Value Handling, Outlier Detection, Supervised Learning, and Unsupervised Learning**.

---

## 🧹 Data Preprocessing

### 1. Feature Scaling

* **[Normalization](NORMALIZATION.ipynb)**
  Scales numerical features to a common range, typically between 0 and 1.

* **[Standardization](standarlization.ipynb)**
  Transforms data so that it has a mean of 0 and a standard deviation of 1.

### 2. Categorical Encoding

* **[Ordinal Encoding](ordinal_encoding.ipynb)**
  Converts ordered categorical variables into numerical values while preserving their order.

* **[One-Hot Encoding](one_hot_encoding.ipynb)**
  Converts categorical variables into separate binary columns.

### 3. Column Transformer

* **[Column Transformer](Column_Transformer.ipynb)**
  Applies different preprocessing techniques to different columns of a dataset.

### 4. Scikit-Learn Pipeline

#### Without Pipeline

* **[Titanic – Without Pipeline](titanic_without_using_pipeline.ipynb)**
* **[Cars – Without Pipeline](cars-without-using-pipelines.ipynb)**

#### With Pipeline

* **[Titanic – Using Pipeline](titanic_using_pipeline.ipynb)**

### 5. Feature Transformation

* **[Function Transformer](Column_Transformer.ipynb)**
* **[Power Transformer](Power_transformer.ipynb)**

Power transformation is useful for reducing skewness and making data distributions more suitable for machine learning algorithms.

---

## 🔢 Binning & Binarization

* **[Binarization](binarization.ipynb)**
  Converts numerical values into binary values such as 0 and 1.

* **[Discretization](Discretization.ipynb)**
  Converts continuous numerical variables into discrete intervals or bins.

---

## 🩹 Missing Value Handling & Imputation

### 1. Handling Mixed Variables

* **[Handle Mixed Variables](HANDLE_MIXED_VARIABLE_01.ipynb)**
* **[Handle Mixed Date & Time](handle_mixed_date,time.ipynb)**

### 2. Imputation Techniques

* **[Arbitrary Value Imputation](imputing-numerical-data/arbitrary-value-imputation.ipynb)**
* **[Mean-Median Imputation](mean_median_imputation.ipynb)**
* **[Complete Case Analysis](Complete_case_anyalyist.ipynb)**
* **[Frequent Value Imputation](frequent-value-imputation.ipynb)**
* **[KNN Imputer](knn_imputer.ipynb)**
* **[MICE](MICE.ipynb)**

**KNN Imputer** uses information from nearby data points to estimate missing values.

**MICE (Multiple Imputation by Chained Equations)** iteratively predicts missing values using other variables in the dataset.

---

## 🚨 Outlier Detection

Outliers are observations that differ significantly from the majority of the data.

### Techniques Covered

* **[Z-Score](z_score.ipynb)**
  Measures how many standard deviations a data point is away from the mean.

* **[IQR Method](IQR.ipynb)**
  Uses the Interquartile Range (IQR) to detect outliers and works particularly well with skewed distributions.

---

# 🤖 Machine Learning Algorithms

## 🟢 Supervised Learning

Supervised learning uses labeled data to learn a mapping between input features and target values.

### 1. Decision Tree

**[Decision Tree](Decision_Tree_ibm.ipynb)**

A tree-based supervised learning algorithm that makes predictions by splitting data based on feature conditions.

### 2. K-Nearest Neighbors

**[KNN Algorithm](KNN_ibm.ipynb)**

Predicts the class or value of a new data point based on its K nearest training examples.

### 3. Random Forest

**[Random Forest](Random_forest_ibm.ipynb)**

An ensemble learning algorithm that combines multiple Decision Trees to produce more accurate and stable predictions.

### 4. Support Vector Machine

**[SVM](SVM_ibm.ipynb)**

Finds an optimal decision boundary (hyperplane) to separate different classes. It can also be used for regression.

---

## 🟣 Unsupervised Learning

Unsupervised learning discovers patterns and structures in data without labeled target values.

### 1. K-Means Clustering

**[K-Means](K_Mean.ipynb)**

Groups similar data points into **K clusters** based on their distance from cluster centroids.

### 2. Hierarchical Clustering

**[Hierarchical Clustering](Hierarchical.ipynb)**

Builds a hierarchy of clusters and represents the relationships between data points using a tree-like structure.

### 3. Agglomerative Clustering

**[Agglomerative Clustering](Agglomerative_Clustering.ipynb)**

A bottom-up hierarchical clustering approach that starts with individual data points and progressively merges similar clusters.

---

## 📊 Topics Covered

| Category            | Topics                                                          |
| ------------------- | --------------------------------------------------------------- |
| **Feature Scaling** | Normalization, Standardization                                  |
| **Encoding**        | Ordinal Encoding, One-Hot Encoding                              |
| **Preprocessing**   | Column Transformer, Pipeline, Function Transformer              |
| **Transformation**  | Power Transformer, Binarization, Discretization                 |
| **Missing Values**  | Mean-Median, Arbitrary Value, Frequent Value, KNN Imputer, MICE |
| **Outliers**        | Z-Score, IQR                                                    |
| **Supervised ML**   | Decision Tree, KNN, Random Forest, SVM                          |
| **Unsupervised ML** | K-Means, Hierarchical, Agglomerative Clustering                 |

---

## 🎯 Learning Goal

The goal of this training is to build a strong foundation in **Machine Learning data preprocessing and algorithms**, with hands-on implementation using **Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-Learn**.
