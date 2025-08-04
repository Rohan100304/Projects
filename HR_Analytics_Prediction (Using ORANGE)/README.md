# 🟧 HR Attrition Prediction using Orange Data Mining

This project demonstrates the use of **Orange Data Mining Tool** to build a machine learning pipeline for predicting employee attrition. It highlights skills in visual workflow creation, data preprocessing, model building, and result interpretation.

---

## 🎯 Project Objective

To simulate a real-world attrition prediction scenario by introducing missing data and building a complete ML pipeline using Orange's drag-and-drop visual interface.

---

## 🔧 Tools & Technologies

- Orange 3 (Visual Data Mining)
- HR Analytics Dataset (cleaned version)
- Widgets used: File, Impute, Normalize, Select Columns, Logistic Regression, Decision Tree, Random Forest, Confusion Matrix, Data Table, Test & Score

---

## 📁 Workflow Steps

1. **Data Modification**: ~5000 random cells removed to simulate missing data.
2. **Preprocessing**:
   - Imputed missing values using model-based and average strategies.
   - Normalized features for better model performance.
3. **Data Splitting**:
   - Modeling Dataset: Rows with known attrition.
   - Prediction Dataset: Rows with unknown attrition.
4. **Modeling**:
   - Trained and tested models using cross-validation.
   - Evaluated performance using accuracy, precision, recall, and F1-score.
5. **Prediction**:
   - Predicted missing target values using the best-performing model.

---

## 🧩 Orange Workflow

![Orange Workflow](Orange_Pics/Model_Img.png)

---

## 📊 Evaluation Results

| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 83.3%    | 0.86      | 0.79   | 0.82     |
| Decision Tree       | 87.3%    | 0.89      | 0.84   | 0.86     |
| Random Forest       | 93.1%    | 0.96      | 0.88   | 0.92     |

> ✅ Random Forest gave the best performance.

---

## 📸 Model Output Screenshots

| Logistic Regression | Decision Tree | Random Forest |
|---------------------|---------------|----------------|
| ![images/LR_CM.png](Orange_Pics/Logestic_eval.png) | ![images/DT_CM.png](Orange_Pics/Decision_tree_elva.png) | ![images/RF_CM.png](Orange_Pics/random_forest_eval.png) |

---

## 🧪 Sample Images from EDA Process

| Attrition Distribution | Age Distribution | Education Qualification | Department |
|------------------------|------------------|--------------------------|------------|
| ![Attrition Dist](EDA_sample_pics/atttrition_count.png) | ![Age](EDA_sample_pics/Age_distribution.png) | ![Education](EDA_sample_pics/Education_qualification.png) | ![Department](EDA_sample_pics/department.png) |


## 📌 Key Takeaways

- Orange is highly effective for rapid prototyping and ML experimentation.
- Workflow-based modeling is transparent and beginner-friendly.
- Ensemble models (like Random Forest) yield better results with minimal tuning.

---

## 📂 How to Run

1. Install Orange → [https://orangedatamining.com](https://orangedatamining.com)
2. Open Orange → Load the provided `.ows` workflow
3. Run each widget to replicate the pipeline and results

---

## 🙋 Author

**Rohan Prabhakar**  
A hands-on machine learning enthusiast, passionate about automation and visual data modeling.

---
