## 📌 Project Overview

### **Customer Segmentation using Clustering and Autoencoders**

This project focuses on segmenting customers based on their purchasing behavior using unsupervised learning. Traditional methods like PCA often fail to capture complex, non-linear patterns in high-dimensional data. To address this, we implement **autoencoders** for non-linear dimensionality reduction, followed by clustering algorithms to identify meaningful customer segments.

---

### 🧾 Dataset
- **UK Online Retail Dataset** (UCI Machine Learning Repository)
- 541,000+ transactions with fields like:
  - `InvoiceNo`, `Quantity`, `UnitPrice`, `CustomerID`, `InvoiceDate`, `Country`

---

### 🔍 Objectives
- Clean and preprocess retail transaction data
- Engineer **RFM** features (Recency, Frequency, Monetary)
- Reduce dimensions using a deep **autoencoder**
- Apply clustering algorithms:
  - **K-Means**
  - **Gaussian Mixture Models (GMM)**
  - **DBSCAN**
- Evaluate clusters using **Silhouette Score** and visualizations

---

### 🔑 Key Results
- Autoencoders helped uncover complex structures in the data
- **DBSCAN** showed significant improvement after encoding (Silhouette Score ↑ from 0.62 to 0.79)
- **K-Means** improved slightly; **GMM** slightly decreased after encoding
- Compressed representations led to more distinct customer segments

---

> 📄 For detailed metrics, visualizations, and interpretation, please refer to [`CSF415_G6_E2 (1).ipynb`](./CSF415_G6_E2(1).ipynb) and the final project report.
