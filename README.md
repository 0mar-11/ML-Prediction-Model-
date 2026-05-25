<img width="1591" height="723" alt="image" src="https://github.com/user-attachments/assets/258417f6-548e-4d85-9163-6058e9d06055" /># ⚽ FIFA Player Value Prediction - Machine Learning Project

A comprehensive machine learning project that predicts football player market values and performance tiers using regression and classification algorithms. Built with Python, Scikit-learn, and Pandas.

---

## ✨ Project Overview

This project analyzes FIFA player data to:
- 🎯 **Regression Task**: Predict player market value (in millions €) based on attributes like age, position, overall rating, and stats
- 🏷️ **Classification Task**: Categorize players into performance tiers (Low/Medium/High)
- 🔍 **Feature Engineering**: Create polynomial features and apply regularization to prevent overfitting
- 📊 **Model Evaluation**: Compare multiple algorithms using R², RMSE, MAE, and Accuracy metrics

---

## 🛠️ Tech Stack

- **Language:** Python 3.8+
- **Libraries:** 
  - `pandas`, `numpy` - Data manipulation
  - `scikit-learn` - ML models & preprocessing
  - `matplotlib`, `seaborn` - Visualization
  - `jupyter` - Interactive development
- **Algorithms:**
  - Regression: Linear, Ridge, Lasso, Polynomial Regression
  - Classification: Logistic Regression, Naive Bayes, KNN, Random Forest
- **Techniques:** 
  - Train/Test Split, Cross-Validation
  - Feature Scaling, Outlier Handling (IQR)
  - Regularization (L1/L2), Learning Curves
  - Model Calibration & Probability Analysis

---

## 📂 Dataset

**Source:** FIFA Player Statistics  
**Features:**
| Feature | Description |
|---------|-------------|
| `Name`, `Country`, `Position` | Player identity & role |
| `Age`, `Overall_Rating`, `Future Potential` | Player attributes |
| `Team`, `Value Per M$` | Club & market value (target) |
| `Total_Stats Score` | Aggregated performance metric |

**Target Variables:**
- Regression: `Value Per M$` (continuous)
- Classification: `Performance_Tier` (Low/Medium/High)

---

## 🚀 Installation & Usage

### 1. Clone the Repository
```bash
git clone https://github.com/0mar-11/fifa-ml-prediction.git
cd fifa-ml-prediction
```


















