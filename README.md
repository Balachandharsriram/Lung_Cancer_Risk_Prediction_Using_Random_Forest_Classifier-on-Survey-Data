# 🚀 Lung Cancer Risk Prediction Using Random Forest Classifier

![Lung Cancer](https://img.shields.io/badge/Project-Lung%20Cancer%20Prediction-brightgreen?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge)
![Machine Learning](https://img.shields.io/badge/ML-Random%20Forest-orange?style=for-the-badge)

## 📝 Overview
This project implements a **Lung Cancer Risk Prediction System** using a Random Forest Classifier on survey data.  
The goal is to analyze various lifestyle and health factors to predict the risk of lung cancer, providing a data-driven approach to early warning.

## 🔍 Dataset
- **Source:** Survey on lung cancer indicators.
- **Features:** 
  - GENDER
  - AGE
  - SMOKING
  - YELLOW_FINGERS
  - ANXIETY
  - PEER_PRESSURE
  - CHRONIC DISEASE
  - FATIGUE
  - ALLERGY
  - WHEEZING
  - ALCOHOL CONSUMING
  - COUGHING
  - SHORTNESS OF BREATH
  - SWALLOWING DIFFICULTY
  - CHEST PAIN
- **Target:** Lung Cancer Risk

## 🚀 Technologies Used
- **Python** 🐍
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Scikit-learn** for model building & evaluation
- **Matplotlib & Seaborn** for data visualization

## 🛠️ Implementation Highlights
- Loaded & explored the dataset to identify any missing values.
- Used label encoding for categorical data.
- Trained a **Random Forest Classifier** to predict lung cancer risk.
- Evaluated the model using metrics like accuracy score and confusion matrix.

## 📊 Results
- Achieved high prediction accuracy on the test set.
- Random Forest provided robust predictions by handling feature importance and minimizing overfitting.

## 📈 Visualization
Graphs were plotted to understand the distribution of features and the model performance.

## 🚀 How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/lung-cancer-risk-prediction.git
    cd lung-cancer-risk-prediction
    ```

2. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Lung_Cancer_Risk_Prediction_Using_Random_Forest_Classifier_on_Survey_Data.ipynb
    ```

4. Run all the cells and explore the results.

## 🏆 Future Improvements
- Try other ensemble models like Gradient Boosting or XGBoost.
- Deploy the model using **Flask** or **Streamlit** for real-time predictions.
- Integrate SHAP or LIME for interpretability.

## 🤝 Contributing
Pull requests are welcome! If you have suggestions to improve this project, feel free to fork the repo and submit a PR.

## ✨ Acknowledgments
- Special thanks to the creators of the lung cancer survey dataset.
- Thanks to the open-source community for powerful libraries.

---

> ⭐ **If you like this project, give it a star on GitHub and follow for more!**
