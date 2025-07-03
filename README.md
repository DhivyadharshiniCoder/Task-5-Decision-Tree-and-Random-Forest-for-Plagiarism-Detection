# 📚 Task 5 – Decision Tree and Random Forest for Plagiarism Detection

This task enhances the plagiarism checker by using **Decision Tree** and **Random Forest** models to classify sentence pairs as plagiarised or not based on their similarity score.

---

## 📁 Dataset Used

We use the output from Task 3: `similarity_output_task3.csv`, which includes:

- `Similarity_Score`: Cosine similarity between two sentences
- `Plagiarised`: Binary label (1 = Yes, 0 = No)

---

## 🧠 Models Trained

| Model            | Description                      |
|------------------|----------------------------------|
| Decision Tree    | Trained with max_depth = 3       |
| Random Forest    | 100 estimators for ensemble vote |

---

## ⚙️ Steps Performed

1. Loaded and preprocessed dataset
2. Split data into train and test sets
3. Trained both models
4. Evaluated using Accuracy, F1-score, and Classification Report
5. Visualized Decision Tree
6. Printed feature importance (from Random Forest)

---
Feature Importance (Random Forest): `Similarity_Score ≈ 1.0`
---
## 📸 Output Screenshot
output_task4.png


