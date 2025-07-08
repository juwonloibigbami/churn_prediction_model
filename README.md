
**Churn Prediction Model** 
Predict customer churn using various machine learning algorithms in Python.

**Overview**
This project implements and compares several machine learning models to predict customer churn in a banking dataset. The aim is to identify which algorithm offers the best performance for this classification task.

**Features**
Data preprocessing and exploratory analysis

**Model training and evaluation using:**
We used different models and we checked the evaluations of this model to see which one is better to use. We tried the following model
1. RandomForestClassifier
2. LogisticRegression
3. Support Vector Machine
4. GradientBoostingClassifier and 
5. KNeighborsClassifier


Performance metrics: accuracy, confusion matrix, and classification report

**Dataset**
The project uses the Churn_Modelling.csv dataset, which contains customer data from a bank, including:

Customer demographics (Age, Gender, Geography)

Account information (CreditScore, Balance, Tenure, Number of Products)

Activity indicators (HasCrCard, IsActiveMember)

Target variable: Exited (1 if the customer left, 0 otherwise)

**Project Structure**
text
.
├── churn_prediction_model.ipynb
├── data/
│   └── Churn_Modelling.csv
└── README.md

**Getting Started**
Prerequisites
Python 3.x
Jupyter Notebook or Google Colab

Install Dependencies
Install required Python libraries:
pip install pandas numpy matplotlib seaborn scikit-learn

Running the Notebook
1. Clone this repository:
bash
git clone https://github.com/yourusername/churn-prediction-model.git
cd churn-prediction-model

2. Open churn_prediction_model.ipynb in Jupyter Notebook or upload to Google Colab.

3. Ensure the dataset is available at data/Churn_Modelling.csv.

4. Run all cells to execute the analysis and view results.

**Usage**
Modify the notebook to experiment with different features or algorithms.

Use the evaluation metrics to compare model performance.

Adapt the code for your own churn prediction use cases.

**Results**
The notebook evaluates each model and provides metrics such as accuracy, confusion matrix, and a classification report. 
Based one our dataset, and scalled features, here are the accuracy reult of the evaluation of different models:
1. RandomForestClassifier - 0.8665
2. LogisticRegression - 0.811
3. Support Vector Machine - 0.856
4. KNeighborsClassifier and - 0.83
5. GradientBoostingClassifier - 0.8675

While we can say all the model did well, having over 80%, **but GradientBoostingClassifier is the winner with about 87%**

This allows you to select the best algorithm for your application.

Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

