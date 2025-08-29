# Heart-Disease-Prediction
An assignment given to me by devtown

## 📌 Project Overview
This project implements a **machine learning pipeline** to detect the likelihood of heart disease using the **UCI Heart Disease dataset**.  
The notebook walks through a **day-by-day workflow**, starting from data preprocessing and exploratory data analysis (EDA), to training, evaluation, and interpretation of multiple models.

The primary goal is to build predictive models that can assist in early detection of heart disease, enabling timely diagnosis and prevention.

---

## 📊 Dataset
- **Source:** [Kaggle - Heart Disease Data](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)  
- **Size:** 303 rows × 14 columns  
- **Features:** Age, Sex, Chest Pain Type (cp), Resting BP, Cholesterol, Fasting Blood Sugar, Rest ECG, Max HR, Exercise Induced Angina, Oldpeak, Slope, Major Vessels, Thal, and Target.  
- **Target Variable:** `target` → `1` (disease) / `0` (no disease)

---

## ⚙️ Installation
Clone this repository and install dependencies:

```bash
git clone https://github.com/yourusername/heart-disease-detector.git
cd heart-disease-detector
pip install -r requirements.txt
```

Or run directly in Google Colab using the badge above.

---

## 🚀 Usage
To run the notebook:

1. Download the dataset from Kaggle.
2. Place `kaggle.json` API key in your working directory.
3. Run the notebook cells sequentially.

Example:

```python
import pandas as pd
df = pd.read_csv("heart_disease_uci.csv")
df.head()
```

---

## Tools used
Python Libraries such as Pandas, NumPy, Matplotlib, Seaborn and Scikit-Learn. The project was built on Google Colab

## 📅 Project Workflow

- **Data Preprocessing & EDA**  
  - Data cleaning, handling missing values, and basic visualization.

- **Model Training**  
  - Logistic Regression, KNN, SVM, and initial accuracy testing.

- **Train/Test Split & Normalization**  
  - Data normalization, stratified splitting, and baseline models.

- **Model Evaluation**  
  - Random Forest, feature importance analysis, and cross-validation.

- **Visualization & Prediction**  
  - Confusion matrices, accuracy comparison, and final model selection.

---

## 📈 Results
- Random Forest achieved the **highest accuracy which is 88% **.  
- Feature importance showed that **chest pain type, thal, and maximum heart rate** were among the strongest predictors.  
- The final model provided a good balance between **accuracy and interpretability**.

---

## Programmers information
#### Name: Kazeem Ibrahim Opeyemi
#### Linkedln: Kazeem Ibrahim
#### Github: https://github.com/Ibrazak0020

## 🔮 Future Improvements
- Hyperparameter tuning with GridSearchCV.  
- Incorporating deep learning models.  
- Deployment as a **Flask/Django web app** or **Streamlit dashboard**.  
- Integration with real-world patient data for clinical validation.

---

## 🙏 Acknowledgments
- [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)  
- [Kaggle Dataset Provider](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)  
- Inspired by ML learning tutorials and guided projects.

---

## 📜 License
This project is licensed under the **MIT License** - feel free to use, modify, and distribute.
