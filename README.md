# Machine Learning Foundations

Welcome to the **Machine Learning Foundations** repository! This project contains foundational machine learning implementations, spanning across basic regression and classification tasks. It is divided into two distinct units, each focusing on a different aspect of data science and predictive modeling.

---

## 📂 Repository Contents

### 1. Unit 1: Student Performance Prediction (Regression)
**File:** [`Machine_Learning_Project_Unit_1.ipynb`](./Machine_Learning_Project_Unit_1.ipynb)  
**Dataset:** `StudentsPerformance.csv`

This project focuses on **Regression analysis**, exploring the relationship between different academic scores.
- **Objective:** Predict a student's `Math Score` based on their `Reading Score`.
- **Techniques Used:** 
  - Exploratory Data Analysis (EDA) and Data Visualization (Scatter plots).
  - Correlation Analysis.
  - Linear Regression and Polynomial Regression implementations.
  - Model Evaluation using metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² Score.

### 2. Unit 2: Email Spam Classification (Classification)
**File:** [`Machine Learning Project Unit 2.ipynb`](./Machine%20Learning%20Project%20Unit%202.ipynb)  
**Dataset:** `emails.csv`

This project delves into **Natural Language Processing (NLP)** and **Classification**.
- **Objective:** Classify emails as either `Spam` (1) or `Ham` (0).
- **Techniques Used:**
  - Data Cleaning (removing special characters, handling missing values).
  - Text Vectorization using `TfidfVectorizer` (TF-IDF).
  - Custom implementation of Logistic Regression from scratch.
  - Scikit-learn's `LogisticRegression` with hyperparameter tuning via `GridSearchCV`.
  - Comprehensive Model Evaluation (Accuracy, Precision, Recall, F1-Score, ROC-AUC).
  - Visualizations including Sigmoid curves, Precision-Recall curves, and class distributions.
  - Feature Importance analysis to identify the most common spam and ham words.

---

## 🚀 Getting Started

### Prerequisites
To run the Jupyter Notebooks in this repository, you will need the following Python libraries installed:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Running the Notebooks
You can run these notebooks locally using Jupyter Notebook/Lab or seamlessly open them in **Google Colab** (as originally designed).

1. Clone this repository:
   ```bash
   git clone https://github.com/omen18/Machine-Learning.git
   cd Machine-Learning
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open the desired `.ipynb` file and execute the cells sequentially. Make sure to download or upload the respective datasets (`StudentsPerformance.csv` and `emails.csv`) to your environment before running the notebooks.

---

## 🛠️ Technologies Used
- **Python 3**
- **Pandas & NumPy** (Data Manipulation)
- **Matplotlib & Seaborn** (Data Visualization)
- **Scikit-Learn** (Machine Learning Modeling)
