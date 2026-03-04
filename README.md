# Medical-Insurance-Cost-Prediction
Machine Learning project to predict medical insurance charges using Linear Regression.

# 🏥 Medical Insurance Cost Prediction

A Machine Learning project to predict **individual medical insurance charges** using Linear Regression.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

---

## 📋 Project Overview

This project predicts the **medical insurance cost** (charges) of a person based on their:
- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region

Built using **Linear Regression** with proper data preprocessing and visualization.

---

## 📊 Dataset

**File:** `insurance.csv`  
**Rows:** 1338  
**Columns:** 7

### Features:
| Column     | Description                          | Type     |
|------------|--------------------------------------|----------|
| age        | Age of primary beneficiary           | Integer  |
| sex        | Gender (male/female)                 | Categorical |
| bmi        | Body Mass Index                      | Float    |
| children   | Number of children                   | Integer  |
| smoker     | Smoking status (yes/no)              | Categorical |
| region     | Residential area                     | Categorical |
| **charges**| Individual medical costs (Target)   | Float    |

---

## 🛠 Technologies & Libraries

- Python 3
- NumPy
- Pandas
- Matplotlib & Seaborn
- Scikit-learn

---

## 📁 Project Structure

```
Medical-Insurance-Cost-Prediction/
├── Medical_Insurance_Cost_Prediction.ipynb   # Main Jupyter Notebook
├── insurance.csv                             # Dataset
├── README.md
```

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Medical-Insurance-Cost-Prediction.git
   cd Medical-Insurance-Cost-Prediction
   ```

2. **Install dependencies**
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
   ```

3. **Run Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
   Open `Medical_Insurance_Cost_Prediction.ipynb`

---

## 📈 Results

| Data          | R² Score     |
|---------------|--------------|
| Training Data | **0.7515**   |
| Test Data     | **0.7447**   |

**Model Performance:** Good fit with ~74.5% accuracy on unseen data.

---

## 💡 Example Prediction

**Input:**
```python
age = 31, sex = female (1), bmi = 25.74, children = 0, 
smoker = no (1), region = southeast (0)
```

**Predicted Insurance Cost: $3760.08**

---

## 🔮 Future Improvements

- Try advanced models (Random Forest, XGBoost, Gradient Boosting)
- Hyperparameter tuning
- Feature engineering
- Deploy as web app (Streamlit / Flask)

---

## 👩‍💻 Made with ❤️ by Inayat Fatema Jafri
