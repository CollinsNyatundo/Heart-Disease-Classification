# Heart Disease Classification Project

## Overview

The Heart Disease Classification project aims to develop a machine learning model that predicts the presence of heart disease in patients based on various health parameters. This project utilizes a dataset containing medical attributes and employs different classification algorithms to identify the best-performing model.

## Table of Contents

- [Project Description](#project-description)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Conclusion](#conclusion)
- [License](#license)

## Project Description

The objective of this project is to analyze the relationship between various health indicators and the likelihood of heart disease. By employing machine learning techniques, the project seeks to provide a predictive model that can assist healthcare professionals in diagnosing heart conditions more effectively.

### Key Steps in the Project:

1. **Data Preprocessing**: Cleaning and preparing the dataset for analysis.
2. **Exploratory Data Analysis (EDA)**: Understanding the dataset through visualizations and statistical analysis.
3. **Model Development**: Building and training various classification models.
4. **Model Evaluation**: Assessing the performance of the models using appropriate metrics.
5. **Results Interpretation**: Analyzing the results to derive insights and conclusions.

## Dataset

The dataset used in this project is sourced from the UCI Machine Learning Repository and consists of various health attributes related to heart disease. The key features include:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Serum Cholesterol
- Fasting Blood Sugar
- Resting Electrocardiographic Results
- Maximum Heart Rate Achieved
- Exercise Induced Angina
- ST Depression
- Slope of the Peak Exercise ST Segment
- Number of Major Vessels
- Thalassemia
- Target Variable (Presence of Heart Disease)

## Technologies Used

- **Python**: Programming language used for data analysis and model building.
- **Pandas**: Library for data manipulation and analysis.
- **NumPy**: Library for numerical computations.
- **Matplotlib**: Library for data visualization.
- **Seaborn**: Statistical data visualization library based on Matplotlib.
- **Scikit-learn**: Machine learning library for building and evaluating models.

## Installation

To run this project locally, you will need to have Python installed along with the required libraries. You can install the necessary packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/CollinsNyatundo/Heart-Disease-Classification.git
   cd Heart-Disease-Classification
   ```

2. **Run the Jupyter Notebook**:
   Launch Jupyter Notebook and open the `Heart-Disease-Classification.ipynb` file.

3. **Follow the Notebook Cells**:
   Execute each cell sequentially to preprocess the data, perform EDA, build models, and evaluate their performance.

## Model Evaluation

The project evaluates multiple classification algorithms, including:

- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machine (SVM)

The models are assessed using metrics such as accuracy, precision, recall, and F1-score. The best-performing model is selected based on these metrics.

### Example of Model Evaluation Results:

- **Logistic Regression**: Accuracy: 85%
- **Random Forest**: Accuracy: 90%
- **SVM**: Accuracy: 88%

## Conclusion

The Heart Disease Classification project successfully demonstrates how machine learning can be applied to healthcare data for predictive analytics. The project highlights the importance of data preprocessing, model evaluation, and the selection of the most suitable algorithm for classification tasks.

## License

This project is licensed under the MIT License. See the LICENSE file for more details. 

---

This README provides a comprehensive overview of the Heart Disease Classification project, detailing its purpose, methodology, and outcomes, making it easier for users to understand and utilize the project effectively.

Citations:
[1] https://github.com/CollinsNyatundo/Heart-Disease-Classification/blob/main/Heart-Disease-Classification.ipynb
