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
### 📸 Screenshots
<img width="1774" height="679" alt="image" src="https://github.com/user-attachments/assets/4a5e8e8c-2f0e-441a-96bd-adbfdf9db04e" />
<img width="1635" height="778" alt="image" src="https://github.com/user-attachments/assets/aa5194ad-9cff-4a22-b788-80f2005943a1" />
<img width="1624" height="836" alt="image" src="https://github.com/user-attachments/assets/def76708-47f0-4cc8-8e94-7ae0da0f2d2f" />
<img width="1633" height="829" alt="image" src="https://github.com/user-attachments/assets/44a0b3bf-9aaf-4f11-9c62-2a83aaf76338" />
<img width="1772" height="829" alt="image" src="https://github.com/user-attachments/assets/8f912850-26cb-4a18-9772-6783bf4b69ba" />
<img width="987" height="121" alt="image" src="https://github.com/user-attachments/assets/a2c6a3f4-1537-4038-a085-2e0e50fc66b6" />
<img width="1743" height="824" alt="image" src="https://github.com/user-attachments/assets/36fad928-8a91-4a76-8871-b96efce0058f" />
<img width="1546" height="776" alt="image" src="https://github.com/user-attachments/assets/492280f3-063d-4b08-8c0d-80b62c0e8b15" />
<img width="1480" height="826" alt="image" src="https://github.com/user-attachments/assets/7ae6755a-203d-4a84-8ffb-07a576338e42" />

<img width="1088" height="724" alt="image" src="https://github.com/user-attachments/assets/285fcbd4-3330-4c3c-9cd5-358c5b596c15" />
<img width="1475" height="838" alt="image" src="https://github.com/user-attachments/assets/917cf53a-7648-449f-89a3-a0f27078d0e9" />
<img width="1055" height="692" alt="image" src="https://github.com/user-attachments/assets/f786a8a5-2e6e-4b8e-9cfa-5ae0c35cd6a7" />
<img width="1338" height="831" alt="image" src="https://github.com/user-attachments/assets/fd994bcf-6947-41ed-b6b3-bcf323482f7b" />
<img width="1148" height="832" alt="image" src="https://github.com/user-attachments/assets/ab46a4bf-3ccb-4f52-9975-653edeeb356d" />

















