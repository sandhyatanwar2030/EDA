# 🚢 Titanic Survival Prediction

> An end-to-end Machine Learning project that predicts passenger survival on the Titanic using **Random Forest**, achieving **83.28% Cross-Validation Accuracy**. This project demonstrates the complete data science workflow—from exploratory data analysis (EDA) to feature engineering, model building, evaluation, and hyperparameter tuning.

---

## 📌 Project Overview

The Titanic dataset is one of the most well-known datasets in machine learning. In this project, I built a classification model to predict whether a passenger survived the disaster based on demographic and travel-related features.

This project was created as my **first end-to-end Data Science portfolio project** and focuses not only on model performance but also on explaining the reasoning behind every step through storytelling-style analysis.

---

## 🎯 Objectives

* Perform thorough Exploratory Data Analysis (EDA)
* Handle missing values and preprocess data
* Engineer meaningful features
* Compare multiple machine learning algorithms
* Tune the best-performing model
* Evaluate model performance using Cross Validation and Test Accuracy

---

# 📊 Exploratory Data Analysis (EDA)

Some of the key insights discovered during analysis include:

### 👩 Gender was the strongest predictor

* Female survival rate: **74.2%**
* Male survival rate: **18.9%**

### 🏆 Passenger Class mattered

* First-class passengers had significantly higher survival chances.
* Third-class passengers experienced the lowest survival rate.

### 👨‍👩‍👧 Family Size helped

Passengers travelling with **2–4 family members** survived more often than solo travellers or very large families.

### 🎩 Title Extraction

Passenger titles (Mr, Mrs, Miss, Master, etc.) were extracted from names and became one of the **Top 3 most important features** in the final model.

---

# ⚙️ Machine Learning Workflow

* Data Cleaning
* Missing Value Treatment
* Feature Engineering
* Feature Encoding
* Train-Test Split
* Model Training
* Cross Validation
* Hyperparameter Tuning
* Model Evaluation
* Feature Importance Analysis

---

# 🤖 Models Compared

| Model                   | Test Accuracy | Cross Validation |
| ----------------------- | ------------: | ---------------: |
| Logistic Regression     |         78.8% |     81.7% ± 0.9% |
| Decision Tree           |         76.5% |     77.6% ± 3.6% |
| ✅ Random Forest (Tuned) |     **83.2%** |       **83.28%** |

---

# 🏆 Best Model

### Random Forest Classifier

**Performance**

* ✅ Test Accuracy: **83.2%**
* ✅ Cross Validation Accuracy: **83.28%**

The Random Forest model produced the best balance between bias and variance and outperformed the other algorithms tested.

---

# 📈 Feature Importance

The most influential features were:

1. Sex
2. Title (Engineered Feature)
3. Fare
4. Passenger Class
5. Age
6. Family Size

---

# 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

# 📂 Project Structure

```
titanic-survival-prediction/
│
├── titanic_project.ipynb      # Complete notebook
├── charts/                    # Saved visualizations
├── README.md
└── dataset/
    ├── train.csv
    └── test.csv
```

---

# 📷 Visualizations

The project includes multiple visualizations, including:

* Survival Distribution
* Survival by Gender
* Survival by Passenger Class
* Age Distribution
* Fare Distribution
* Correlation Heatmap
* Feature Importance Plot

---

# 🚀 Future Improvements

* Implement XGBoost and LightGBM
* Engineer Deck feature from Cabin
* Perform advanced hyperparameter tuning
* Build a Streamlit web application
* Deploy the model online
* Improve Kaggle leaderboard performance

---

# 📚 Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Feature Engineering
* Data Visualization
* Machine Learning
* Classification
* Cross Validation
* Hyperparameter Tuning
* Model Evaluation
* Feature Importance Interpretation

---

# 💡 Key Takeaways

This project strengthened my understanding of the complete machine learning lifecycle, from raw data exploration to building and evaluating predictive models. It also reinforced the importance of feature engineering and model comparison in improving predictive performance.

---

## 👩‍💻 About Me

**Sandhya Tanwar**

🎓 B.Tech in Computer Science Engineering
🏫 TITS Bhiwani

Aspiring **Data Scientist** passionate about Machine Learning, Data Analytics, and solving real-world problems through data.

---

## ⭐ If you found this project useful

If you like this project, consider giving it a **⭐ Star** on GitHub. It motivates me to build and share more data science projects!
