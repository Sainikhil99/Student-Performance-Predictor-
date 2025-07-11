
---

## 📊 Dataset Info

- 📁 Source: [StudentsPerformance.csv](https://raw.githubusercontent.com/selva86/datasets/master/StudentsPerformance.csv)
- 🔢 1000 student records
- 🧠 Features:
  - Gender
  - Race/Ethnicity
  - Parental level of education
  - Lunch type (standard/free)
  - Test preparation course (completed/none)
  - Math score, Reading score, Writing score

---

## 🎯 Objective

- Predict whether a student **passes (1)** or **fails (0)** based on the above features
- A pass means the student must pass the every subject  is ≥ 40**

---

## 🔨 Steps Performed

### ✅ 1. Data Exploration
- Checked dataset shape, unique values, and basic stats

### ✅ 2. Feature Engineering
- Created a new column `pass` based on the average of 3 scores

### ✅ 3. Data Cleaning + Encoding
- One-hot encoded categorical variables (e.g., gender, lunch)
- Removed redundant columns (`average_score`)

### ✅ 4. Model Building
- Logistic Regression (baseline model)
- Random Forest Classifier (advanced model)

### ✅ 5. Evaluation
- Accuracy score
- Confusion matrix (with heatmap)
- Classification report (precision, recall, F1-score)

### ✅ 6. Visualization
- Confusion matrix heatmap using Seaborn

---

## 📈 Model Performance

| Model                | Accuracy | Comments                     |
|---------------------|----------|------------------------------|
| Logistic Regression | 98.5%    | Baseline, fast & interpretable |
| Random Forest       | ~99%     | More powerful & robust        |

---

## 🧠 What I Learned

- How to preprocess real-world data (categorical → numerical)
- One-hot encoding and avoiding dummy variable trap
- When and how to use classification models like Logistic Regression & Random Forest
- Importance of evaluation metrics: accuracy, precision, recall, F1-score
- How to visualize confusion matrices
- Handling slight class imbalance in binary classification
- Creating GitHub-ready ML projects

