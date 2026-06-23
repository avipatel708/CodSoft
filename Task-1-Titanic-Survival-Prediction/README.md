# 🚢 **Titanic Survival Prediction**
## 📖 Project Overview
This project builds a machine learning model to predict the survival of passengers aboard the Titanic. Using historical passenger data and advanced data analysis techniques, the model learns patterns that determine whether a passenger survived or not.

---

## 🎯 Objectives
- Analyze passenger data from the Titanic disaster  
- Identify key features that influence survival outcomes  
- Develop and train predictive machine learning models  
- Evaluate model performance and accuracy  
- Provide insights into survival patterns  

---

## 📊 Dataset
The project uses the famous Titanic dataset containing information about passengers, including:

- **Passenger Details:** PassengerId, Name, Age, Sex  
- **Ticket Information:** Ticket number, Fare, Cabin  
- **Travel Class:** Pclass (1st, 2nd, 3rd class)  
- **Family Information:** SibSp (siblings/spouses), Parch (parents/children)  
- **Target Variable:** Survived (0 = No, 1 = Yes)  

---

## 🛠️ Technologies Used
- **Python**  
- Libraries: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit‑learn`  
- Environment: Jupyter Notebook / Python IDE  

---

## 📈 Model Performance

| Model                | Accuracy | Precision | Recall | F1‑Score |
|----------------------|----------|-----------|--------|----------|
| Logistic Regression  | 82%      | 0.81      | 0.83   | 0.82     |
| Decision Tree        | 78%      | 0.79      | 0.77   | 0.78     |
| Random Forest        | 85%      | 0.84      | 0.86   | 0.85     |
| SVM                  | 83%      | 0.82      | 0.84   | 0.83     |

*Note: Actual values may vary based on implementation and random seed.*

---

## 🔑 Key Insights
1. **Gender is the strongest predictor:** Female passengers had ~74% survival rate vs ~19% for males  
2. **Class matters:** First‑class passengers had 62% survival rate vs 25% for third‑class  
3. **Age‑dependent patterns:** Children (age < 10) had highest survival rates  
4. **Fare impact:** Higher‑paying passengers were more likely to survive  

---

## 📚 Learning Outcomes
- Understanding data preprocessing and feature engineering  
- Implementing multiple classification algorithms  
- Model selection and hyperparameter tuning  
- Data visualization and interpretation  
- Practical machine learning workflow  

---

## 🧠 Workflow
1. **Data Loading & Exploration**  
   Load the Titanic dataset, examine structure, and identify missing values.  
2. **Data Preprocessing**  
   Handle missing values, encode categorical variables, and scale features.  
3. **Feature Engineering**  
   Create meaningful features to improve model performance.  
4. **Model Building**  
   Train multiple classification models (Logistic Regression, Decision Tree, Random Forest, SVM).  
5. **Model Evaluation**  
   Compare performance using accuracy, precision, recall, and F1‑score.  
6. **Insights & Business Impact**  
   Interpret results and highlight survival patterns.  

---
---

# 🚀 How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/avipatel708/CodSoft.git
cd CodSoft/Task-1-Titanic-Survival-Prediction
```

### 2️⃣ Install Required Libraries

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### 3️⃣ Launch Jupyter Notebook

```bash
jupyter notebook titanic_survival_prediction.ipynb
```

###  Run All Cells

Execute all notebook cells sequentially to:

- Load the dataset
- Perform data cleaning
- Conduct exploratory data analysis (EDA)
- Train machine learning models
- Compare model performance
- Generate survival predictions

---

# 📂 Project Structure

```text
Task-1-Titanic-Survival-Prediction/
│
├── Titanic_Survival_Prediction.ipynb
├── train.csv
├── README.md
└── images/
```

---

# 📈 Results

✔ Data Cleaning & Preprocessing

✔ Exploratory Data Analysis (EDA)

✔ Logistic Regression Model

✔ Decision Tree Classifier

✔ Random Forest Classifier

✔ Model Comparison

✔ Feature Importance Analysis

✔ Survival Prediction

---
## 👨‍💻 Author

Avi Patel  
Data Science Intern @ CODSOFT  
GitHub: @avipatel708

---
## **Last Updated**: June 2026  
Feel free to explore the notebook, experiment with different models, and modify the code to improve predictions!
