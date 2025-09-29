# 🌸 Iris Dataset – Model Comparison & Clustering

This project explores the famous **Iris dataset** using several machine learning models.  
The goal is to compare performance across supervised classifiers and an unsupervised clustering method (KMeans).  
All results are visualized and exported as `.png` files for easy sharing and documentation.

---

## 📊 What’s Inside

### 1. **Dataset**
- Dataset: [`sklearn.datasets.load_iris`](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)  
- Features: 4 flower measurements (`sepal length`, `sepal width`, `petal length`, `petal width`)  
- Target: 3 classes (`setosa`, `versicolor`, `virginica`)  

### 2. **Models Trained**
We train and evaluate a set of supervised classifiers:
- **Logistic Regression**
- **Support Vector Machine (Linear Kernel)**
- **Decision Tree**
- **Random Forest**
- **Neural Network (MLP)**

Additionally, we test **KMeans clustering** (unsupervised) and compare how well the clusters align with the real species
