# capstone-project
# Customer Segmentation with KMeans & AI Support

## Project Overview
This project aims to segment mobile phone customers based on their specifications using **KMeans clustering**.  
AI support (via Replicate API) is used to classify clusters into human-readable categories (Budget, Mid-range, Premium).  
The goal is to help businesses identify customer groups and target them effectively.

---

## Dataset
- [Dataset (test.csv) - in repo](./test.csv)  
- [Dataset Source (Kaggle)](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification)  

---

## Notebook
- [Google Colab Notebook](https://colab.research.google.com/drive/1P-x6V7wdE3jvH9AW1W5_6emNXS-LsM-w?usp=sharing)

---

## Insight & Findings
- The optimal number of clusters was found to be **k = 3**, based on the Silhouette Score.  
- Cluster interpretation using AI:  
  - **Cluster 0** → Budget phones (lower RAM, smaller battery, lower price).  
  - **Cluster 1** → Mid-range phones (balanced specs and price).  
  - **Cluster 2** → Premium phones (higher RAM, better camera, higher price).  

---

## Conclusion & Recommendation
- AI-assisted clustering provides a meaningful categorization of customer segments.  
- Businesses can use this to design **targeted marketing strategies** (e.g., budget phone users may respond better to affordability campaigns).  
- Premium cluster customers can be targeted with **exclusive features & luxury branding**.  

---

## AI Support Explanation
- **LLM (IBM Granite via Replicate API)** was used to classify KMeans clusters into human categories.  
- AI enhanced interpretability by providing **natural language explanations** for each cluster.  
