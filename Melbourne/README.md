# 🏠 Melbourne House Price Prediction – Project Planning

This folder contains **project planning and documentation** for a Data Science case study on **Melbourne House Price Prediction**.

The focus of this section is **methodology, reasoning, and workflow design**, not model deployment or production code.

---

## 📁 Folder Structure
```
Melbourne/
│
├── Data/
│ └── (Dataset reference & notes)
│
├── Diagram/
│ ├── BPMN Diagram/
│ └── Activity Diagram/
│
├── Docs/
│ └── Additional explanations & notes
│
└── README.md
```

---

## 🎯 Objective

To design a **clear and explainable Data Science workflow** for predicting house prices in Melbourne, covering:

- Exploratory Data Analysis (EDA)
- Data leakage identification
- Missing value handling strategy
- Preprocessing pipeline design
- Baseline vs final model planning
- Evaluation & inference flow

---

## 🧠 Key Topics Covered

### 1️⃣ Exploratory Data Analysis (EDA)
- Target identification (`Price`)
- Missing value analysis
- Understanding numerical & categorical features
- Initial data quality assessment

---

### 2️⃣ Data Leakage Considerations
Special attention is given to identifying potential data leakage, such as:
- Unique identifier features (e.g. `Address`)
- Features that may indirectly encode target information
- Decisions on dropping high-risk columns before preprocessing

---

### 3️⃣ Missing Value Strategy
- Numerical features → **Median imputation**
- Categorical features → **Mode imputation**
- High-missing features are imputed (not dropped) if considered informative

---

### 4️⃣ Preprocessing Pipeline Design
- Handling missing values
- One-Hot Encoding for categorical features
- Feature scaling for numerical features
- Use of `Pipeline` and `ColumnTransformer` to avoid leakage

---

### 5️⃣ Feature Analysis (Mutual Information)
- Used as an **optional analysis tool**
- Helps interpret feature–target relationships
- Not mandatory for feature selection

---

### 6️⃣ Modeling Strategy
- Baseline models (Linear & Tree-based)
- Cross-validation on training data
- Model comparison using RMSE (mean & std)
- Final model selection and tuning plan

---

### 7️⃣ Evaluation Metric
**RMSE (Root Mean Squared Error)** is used because:
- Same unit as target (house price)
- Penalizes large prediction errors
- Suitable for regression problems

---

## 📊 Diagrams Included

- ✅ **BPMN Diagram** – end-to-end project flow
- ✅ **Activity Diagrams** – EDA,Preprocessing,MutualInformation,BaselineModel,FinalModel,ModelInference

These diagrams are designed to **communicate the reasoning process**, not just the final result.

---

## ⚠️ Notes

- This folder focuses on **planning & conceptual design**
- Model implementation and experimentation are handled elsewhere
- Diagrams and notes are included to demonstrate **structured Data Science thinking**

---

## 👤 Author

**Raihan**  
Aspiring Data Scientist  
Focused on structured ML workflows, data leakage prevention, and explainable modeling

