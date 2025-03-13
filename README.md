# **Machine Learning Project: Predictive Model Implementation and Optimization**

## **Project Overview**
This project applies machine learning techniques to analyze data and create a predictive model. The workflow includes data preprocessing, model training, optimization, and evaluation to ensure high predictive performance.

## **Project Objectives**
- Retrieve and process data (preferably from PySpark).
- Preprocess and clean data (handling missing values, normalization, etc.).
- Train and evaluate a predictive model.
- Optimize the model using hyperparameter tuning.
- Visualize results and provide insights based on model performance.

## **Data Source**
The dataset used in this project is stored in a structured format and was retrieved using **PySpark**. It consists of various features used to train and validate the model.
The datasets were downloaded from Kaggle.com: https://www.kaggle.com/datasets/uciml/zoo-animal-classification. 

## **Project Workflow**
1. **Data Loading**: The dataset is loaded using PySpark queries.
2. **Data Preprocessing**: Includes handling missing values, feature scaling, and encoding categorical data.
3. **Model Training & Evaluation**: The machine learning model is trained and evaluated for accuracy.
4. **Model Optimization**: Hyperparameter tuning and performance analysis are conducted.
5. **Visualization & Insights**: Data and results are visualized for better interpretation.

## **Model Performance**
- Achieved a classification accuracy of **75%+** or **0.80+ R-squared**, meeting project requirements.
- Evaluated using metrics such as precision, recall, and F1-score.

## **Visualizations**
The project includes various data visualizations generated using **Matplotlib, Seaborn, and Plotly**, providing insights into model performance and feature importance.

## **Repository Structure**
```
├── data/                 # Raw and processed data files
├── notebooks/            # Jupyter notebooks with code implementation
├── models/               # Trained machine learning models
├── visuals/              # Data visualization outputs
├── README.md             # Project documentation
└── .gitignore            # Files to be ignored in version control
```

## **Installation & Requirements**
To run this project locally, install the required dependencies:
```bash
pip install -r requirements.txt
```

## **Usage**
Run the main notebook to execute the machine learning workflow:
```bash
jupyter notebook Final_Project.ipynb
```

## **Contributors**
This project was developed by Don Ross, Melisa Teglas, and Tamya Louis. Each team member contributed to different aspects of the project, including data processing, model development, and visualization.


