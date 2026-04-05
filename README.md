# 📊 Strategic Customer Behavioral Analysis
**An AI-Driven Study by Aditya, Sinchana, Nivetha, Pragya, & Priti**

**ABSTRACT**

This study presents a **Strategic Customer Behavioral Analysis** using unsupervised machine learning to move beyond traditional demographic segmentation. Utilizing a dataset of 2,240 customers, the research employs **Principal Component Analysis (PCA)** for dimensionality reduction and **K-Means Clustering** to identify latent consumer patterns.

Distinguishing this work from standard analytical models, we integrated a **"Human Angle"** by engineering features that measure the psychological tension between **Rational vs. Emotional spending, Digital Engagement,** and **Household Life-Stage Dynamics**. The model successfully identified four distinct strategic personas: *Elite High-Spenders, Budget-Conscious Families, Tech-Savvy Youth,* and *Occasional Shoppers*.

## 🎯 Project Overview
This project moves beyond traditional demographics to analyze the **psychology of consumer behavior**. By applying Unsupervised Machine Learning (K-Means Clustering) and Dimensionality Reduction (PCA), we segmented a customer base into four strategic personas to drive targeted marketing decisions.

## 🧠 The "Human Angle" (Our Strategic Corners)
Unlike standard data projects, our team focused on three specific behavioral indicators:
- **Rational vs. Emotional Spending:** We analyzed the balance between essential purchases (Meat/Fruits) and discretionary/luxury buys (Wine/Gold).
- **Digital Engagement:** We calculated a 'Digital Savvy Score' to identify customers who prefer web-based interactions over traditional physical stores.
- **Life-Stage Dynamics:** We integrated family size and parental status to understand how household pressure shifts spending priorities.

## 🛠️ Technical Implementation
- **Data Engineering:** Custom feature creation including `Total_Spent`, `Loyalty_Index`, and `Digital_Ratio`.
- **Dimensionality Reduction:** Used **PCA** to condense 29 variables into 3 Principal Components for optimized clustering.
- **Clustering Logic:** Applied **K-Means Clustering** with validation via the **Elbow Method** and **Silhouette Scoring**.
- **Visualization:** 3D Scatter Plots, Hierarchical Dendrograms, and Boxenplots for distribution analysis.

## 👥 Strategic Personas Identified
1. **The Elite High-Spenders:** High-income, high-emotional spenders. Highly loyal.
2. **The Budget Families:** Rational spenders focused on essentials with high household pressure.
3. **The Tech-Savvy Youth:** Young, emerging consumers with high digital engagement ratios.
4. **The Occasional Shoppers:** Low-frequency consumers requiring "win-back" marketing strategies.

## 🚀 How to Run
The analysis is contained within the `.ipynb` file. It is optimized for **Google Colab** and requires the `marketing_campaign.csv` dataset provided in this repository.
