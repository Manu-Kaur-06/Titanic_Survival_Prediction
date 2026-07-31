## 🚢 Titanic Survival Prediction using Machine Learning
It predicts Titanic passenger survival using Logistic Regression with Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

### 📖 Project Overview

The **Titanic Survival Prediction** project is a supervised machine learning classification project that predicts whether a passenger survived the Titanic disaster based on historical passenger information.

The project uses the **Titanic dataset** to analyze passenger characteristics, preprocess the data, visualize important patterns, and build a **Logistic Regression** model capable of predicting passenger survival.

---

### 🎯 Problem Statement

The objective of this project is to build a Machine Learning model that predicts whether a Titanic passenger **survived or not** using the following passenger information:

- Passenger Class (Pclass)
- Sex
- Age
- Number of Siblings/Spouses (SibSp)
- Number of Parents/Children (Parch)
- Fare
- Port of Embarkation (Embarked)

#### Target Variable

- **0 → Did Not Survive**
- **1 → Survived**

---

### 📂 Dataset

The project uses the **Titanic Dataset**, which contains passenger demographic and travel information collected from the Titanic disaster.

#### Features Used

| Feature | Description |
|----------|-------------|
| Pclass | Passenger class (1st, 2nd, or 3rd) |
| Sex | Passenger gender |
| Age | Passenger age |
| SibSp | Number of siblings/spouses aboard |
| Parch | Number of parents/children aboard |
| Fare | Ticket fare |
| Embarked | Port where the passenger boarded |

#### Target Variable

| Column | Description |
|----------|-------------|
| Survived | Passenger survival status (0 = No, 1 = Yes) |

---

### ⚙️ Project Workflow

The project follows the complete Machine Learning workflow.

#### 1. Data Loading

- Loaded the Titanic dataset using Pandas.
- Displayed and explored the dataset.

#### 2. Exploratory Data Analysis (EDA)

Performed data analysis by:

- Checking dataset dimensions
- Viewing column information
- Identifying missing values
- Creating count plots
- Creating distribution plots
- Creating a correlation heatmap

#### 3. Data Preprocessing

Prepared the dataset for model training by:

#### Handling Missing Values

- Replaced missing values in the **Age** column using the **mean**.
- Replaced missing values in the **Embarked** column using the **mode**.

#### Encoding Categorical Features

Converted categorical values into numerical values.

**Sex**

| Category | Encoded Value |
|----------|---------------|
| Male | 0 |
| Female | 1 |

**Embarked**

| Category | Encoded Value |
|----------|---------------|
| S | 0 |
| C | 1 |
| Q | 2 |

#### 4. Feature Selection

Separated the dataset into:

- **Features (X)** → Passenger information used for prediction.
- **Target (Y)** → Survival status to be predicted.

#### 5. Train-Test Split

Split the dataset into:

- **80% Training Data**
- **20% Testing Data**

The training data was used to train the model, while the testing data was used to evaluate its performance on unseen data.

#### 6. Model Training

Trained a **Logistic Regression** model using the training dataset.

#### 7. Prediction

Generated predictions for:

- Training dataset
- Testing dataset

Possible prediction values:

- **0 → Did Not Survive**
- **1 → Survived**

#### 8. Model Evaluation

Evaluated the model using the **Accuracy Score** by comparing the predicted values with the actual survival values.

---

### 🤖 Machine Learning Model

#### Algorithm Used

- Logistic Regression

#### Why Logistic Regression?

Logistic Regression is a supervised machine learning algorithm designed for **binary classification** problems.

Since the target variable has only two possible outcomes (**Survived** or **Did Not Survive**), Logistic Regression is an appropriate algorithm for this prediction task.

---

### 📊 Model Performance

| Metric | Accuracy |
|---------|----------|
| Training Accuracy | **80.76%** |
| Testing Accuracy | **78.21%** |

#### Result

The model achieved good performance on both the training and testing datasets.

The small difference between training and testing accuracy indicates that the model learned meaningful patterns without significantly overfitting the training data.

---

### 📈 Data Visualizations

The following visualizations were created during Exploratory Data Analysis (EDA):

- Survival Count Plot
- Gender Distribution
- Survival by Gender
- Passenger Class Distribution
- Survival by Passenger Class
- Embarked Distribution
- Age Distribution
- Fare Distribution
- Correlation Heatmap

---

### 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

### 📌 Conclusion

This project demonstrates the complete end-to-end Machine Learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, prediction, and evaluation.

Using the **Logistic Regression** algorithm, the model successfully predicted passenger survival with a **Training Accuracy of 80.76%** and a **Testing Accuracy of 78.21%**, indicating that it can make reliable predictions on unseen passenger data.

create a layman language paragraph to explain my project in interview also write defition where required 
