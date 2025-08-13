# Bank Customer Churn Prediction

 ## 🤖 Project Overview

This project focuses on predicting customer churn for a bank using a dataset of its customers. The primary objective is to build and evaluate several machine learning models to determine which one most accurately predicts whether a customer will exit the bank.

The notebook provides a complete workflow, from initial data exploration and preprocessing to model training and performance evaluation. It serves as a practical example of how to approach a binary classification problem in a real-world business context.

---

## ✨ Key Features

-   **Exploratory Data Analysis (EDA):**
    -   Loads the customer dataset and examines its structure, data types, and summary statistics.
    -   Identifies and handles missing values to ensure data quality.

-   **Data Preprocessing & Feature Engineering:**
    -   Encodes categorical features (like `Geography` and `Gender`) into numerical formats using one-hot encoding.
    -   Selects the relevant features for modeling and separates the dataset into features (X) and the target variable (y).
    -   Splits the data into training and testing sets to evaluate model performance on unseen data.
    -   Applies **feature scaling** to standardize the feature values, which is crucial for distance-based algorithms like SVM.

-   **Machine Learning Modeling:**
    -   Implements and trains four different classification models:
        1.  **Logistic Regression**
        2.  **Support Vector Machine (SVM)**
        3.  **Decision Tree Classifier**
        4.  **Random Forest Classifier**

-   **Model Evaluation:**
    -   Evaluates each model's performance on the test set using key classification metrics:
        -   **Accuracy Score:** Measures the overall correctness of the predictions.
        -   **Confusion Matrix:** Provides a detailed breakdown of correct and incorrect predictions for each class.
    -   Compares the accuracy of all four models to identify the most effective one for this problem.

---

## 🛠️ Technologies Used

-   **Python 3.x**
-   **Pandas:** For data loading and manipulation.
-   **NumPy:** For numerical operations.
-   **Scikit-learn (sklearn):** For implementing and evaluating machine learning models (Logistic Regression, SVM, Decision Tree, Random Forest), and for preprocessing tasks.
-   **Jupyter Notebook:** As the development environment.

---

## 🚀 How to Run This Project

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```

2.  **Create a virtual environment (optional but recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```
    *(Note: You will need to create a `requirements.txt` file by running `pip freeze > requirements.txt` in your local environment.)*

4.  **Download the dataset:**
    -   Place the `Churn_Modelling.csv` file in the root directory of the project.

5.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook datamining (3).ipynb
    ```

---

## 📁 File Structure
