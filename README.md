# 🚀 Customer Segmentation & Prediction using Machine Learning

## 📌 Project Overview

This project focuses on segmenting customers using clustering techniques and building predictive models for each segment to improve business decision-making.

---

## 🎯 Objectives

* Segment customers into meaningful groups
* Apply multiple clustering algorithms (K-Means, Hierarchical, DBSCAN)
* Build separate Random Forest models for each segment
* Perform hyperparameter tuning
* Generate business insights

---

## 📊 Dataset

* Customer churn dataset
* ~500 records
* Features include customer behavior, tenure, and charges

---

## ⚙️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

## 🧠 Machine Learning Techniques

### 🔹 Clustering

* K-Means (Elbow Method)
* Hierarchical Clustering
* DBSCAN

### 🔹 Classification

* Random Forest

### 🔹 Optimization

* GridSearchCV for hyperparameter tuning

---

## 📈 Results

| Segment   | Accuracy | F1 Score |
| --------- | -------- | -------- |
| Cluster 0 | ~90%     | ~0.88    |
| Cluster 1 | ~88%     | ~0.85    |
| Cluster 2 | ~91%     | ~0.89    |

---

## 📊 Key Insights

* High tenure customers show low churn probability
* Pricing impacts churn significantly
* Different segments require different strategies

---

## 💡 Business Recommendations

* Premium customers → Loyalty programs
* Budget customers → Discounts & offers
* Young customers → Upselling strategies

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
jupyter notebook customer_segmentation.ipynb
```

---

## 📁 Project Structure

```bash
customer-segmentation-ml/
│
├── customer_segmentation.ipynb
├── customer_churn.csv
├── model_evaluation_results.csv
├── segment_profiles.md
├── business_recommendations.pdf
├── README.md
└── requirements.txt
```

---

## 📌 Future Improvements

* Add Streamlit dashboard
* Deploy model
* Real-time prediction API

---

## 🏁 Conclusion

This project demonstrates how machine learning can be used to segment customers and drive data-driven business decisions.

---
