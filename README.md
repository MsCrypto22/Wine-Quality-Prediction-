# Wine Quality Prediction

This project aims to predict wine quality based on physicochemical properties using machine learning techniques. By analyzing a dataset of red and white wines, we develop models to classify wine quality, providing insights into the factors that influence it.

## Table of Contents

- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Models Implemented](#models-implemented)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Dataset

The dataset used in this project is sourced from the UCI Machine Learning Repository:

- **Wine Quality Dataset**: [UCI Machine Learning Repository - Wine Quality Data Set](https://archive.ics.uci.edu/ml/datasets/wine+quality)

This dataset includes chemical properties and quality ratings for red and white variants of the Portuguese "Vinho Verde" wine.

## Features

The dataset comprises the following physicochemical properties:

- **Fixed Acidity**
- **Volatile Acidity**
- **Citric Acid**
- **Residual Sugar**
- **Chlorides**
- **Free Sulfur Dioxide**
- **Total Sulfur Dioxide**
- **Density**
- **pH**
- **Sulphates**
- **Alcohol**
- **Quality** (target variable)

## Installation

To run this project locally, ensure you have Python installed. Clone the repository and install the required packages:

```bash
git clone https://github.com/yourusername/wine-quality-prediction.git
cd wine-quality-prediction
pip install -r requirements.txt
```

## Usage

1. Data Preprocessing**: Clean and preprocess the data to handle missing values and normalize features.
2. Exploratory Data Analysis (EDA)**: Visualize data distributions and relationships between features.
3. Model Training**: Train machine learning models using the preprocessed data.
4. Evaluation**: Assess model performance using metrics such as accuracy, precision, recall, and F1-score.

Detailed instructions and code examples are provided in the Jupyter Notebook included in this repository.

**Models Implemented
**
The following machine learning algorithms are utilized:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- Gradient Boosting Classifier

**Results**

After training and evaluating the models, the Random Forest Classifier achieved the highest accuracy in predicting wine quality. Detailed performance metrics and visualizations are available in the project notebook.

**Contributing**

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

**License**

This project is licensed under the MIT License.

Acknowledgments

- **Dataset Source**: Paulo Cortez, University of Minho, Guimarães, Portugal.
- **Inspiration**: [Wine Quality Prediction Using Machine Learning](https://www.analyticsvidhya.com/blog/2021/04/wine-quality-prediction-using-machine-learning/)

This project serves as a practical application of machine learning techniques in the field of oenology, providing valuable insights into the factors influencing wine quality. 
