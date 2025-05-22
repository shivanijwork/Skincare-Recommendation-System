# 🧴 Skincare Recommendation System (Mini Project)

A machine learning-based content recommendation project that suggests similar skincare products based on their ingredients and predicts product types. Developed as a college mini project to explore real-world ML applications in the skincare domain.

---

## 🔍 What This Project Does

- Recommends similar skincare products using **cosine similarity** on ingredient vectors.
- Classifies products into types (Moisturizer, Serum, Oil, etc.) using **multiple ML models**.
- Visualizes product similarities using **t-SNE + TruncatedSVD**.

---

## 🧪 Tech Stack

- **Python**, **Pandas**, **NumPy**
- **Scikit-learn** (ML models, TF-IDF, dimensionality reduction)
- **Matplotlib**, **Seaborn**, **Bokeh** (visualizations)

---

## 📊 Models Tried

| Model                 | Accuracy |
|----------------------|----------|
| Random Forest        | 55.7%    |
| SVM (Linear Kernel)  | 55.7%    |
| MLP Classifier       | 55.7%    |
| Logistic Regression  | 53.9%    |
| Gradient Boosting    | 49.5%    |
| Decision Tree        | 43.9%    |
| KNN                  | 42.9%    |
| Naive Bayes          | 36.8%    |

📌 *Reasonable accuracy given overlapping ingredients + class imbalance.*

---


