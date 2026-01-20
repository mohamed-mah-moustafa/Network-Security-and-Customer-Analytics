# 📊 AI Clustering & Classification Analysis
### Network Intrusion Detection | Customer Segmentation | Image Processing

## 🌟 Project Overview
This project demonstrates the application of **Unsupervised Learning** (K-Means) and **Supervised Learning** (Perceptron) across three diverse real-world domains. The goal was to extract meaningful patterns from high-dimensional data and provide actionable business insights.

---

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn, OpenCV
* **Key Concepts:** Dimensionality Reduction (PCA), Feature Scaling, One-Hot Encoding, Elbow Method, Stratified Sampling.

---

## 📁 Key Tasks & Implementation

### 1️⃣ Network Intrusion Detection (KDD Dataset)
* **Problem:** Identifying "Normal" vs. "Anomaly" network traffic in a highly imbalanced environment.
* **Approach:** Balanced the dataset using downsampling and applied a **Perceptron** classifier for linear separation.
* **Clustering:** Used K-Means to group traffic and labeled clusters based on majority-vote real-world labels.

### 2️⃣ Mall Customer Segmentation (Retail Analytics)
* **Problem:** Grouping customers to define targeted marketing strategies.
* **Approach:** Processed 17 features using **StandardScaler** and **OneHotEncoder**.
* **Analysis:** Used the **Elbow Method** to find the optimal $K$. 
* **Visualization:** Applied **PCA (Principal Component Analysis)** to compress 17D data into 2D for visual cluster verification and centroid mapping.

### 3️⃣ Agricultural Image Segmentation (Computer Vision)
* **Problem:** Separating plant features from backgrounds based on color profile.
* **Approach:** Reshaped image pixels into a 3D RGB space and applied K-Means to create segmented masks.

---

## 📈 Strategic Business Insights (Task 2)
Based on the segmentation analysis, the following profiles were identified:
* **Cluster 0 (VIPs):** High Income, High Spending. *Strategy: Exclusive preview events and premium loyalty tiers.*
* **Cluster 1 (Budget-Conscious):** Frequent visitors but low spenders. *Strategy: Volume-based discounts and "flash sale" notifications.*
* **Cluster 2 (Untapped Market):** High Income, Low Spending. *Strategy: Personalized marketing to identify specific product interests.*

---

## 🚀 How to Run
1. Open the `.ipynb` file in Google Colab.
2. Ensure you have the following files in your directory:
   - `Sample_KDD(2).csv`
   - `mall_customer.csv`
   - `image_004.JPG`
3. Run all cells to see the visualizations and reports.
