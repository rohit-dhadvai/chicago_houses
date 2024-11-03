
# House Price Prediction

## Description
This project involves predicting house prices in various cities using regression and classification models. The models implemented include Linear Regression, Random Forest, and XGBoost for regression tasks, as well as Logistic Regression and Random Forest for classification tasks. The goal is to analyze the dataset, build predictive models, and evaluate their performance to provide insights into house price determinants.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Models and Methodology](#models-and-methodology)
- [Results](#results)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/rohit-dhadvai/chicago_houses.git
   ```
2. Navigate to the project directory:
   ```bash
   https://github.com/rohit-dhadvai/chicago_houses/tree/main
   ```
3. Install the required libraries:
   ```bash
   pip install pandas
   pip install scikit-learn
   pip install xgboost
   ```

## Usage
- Navigate to this link to open the google collab and run the cells to see the model results:
https://colab.research.google.com/drive/186GudAT_7kUjCEIWmX4ev9do6VNTXNfZ?usp=sharing

## Models and Methodology
- **Regression Models**:
  - Linear Regression: Used for predicting continuous house prices based on various features.
  - Random Forest Regressor: An ensemble method that improves prediction accuracy by averaging multiple decision trees.
  - XGBoost Regressor: A more advanced implementation of gradient boosting that aims for better performance and speed.

- **Classification Models**:
  - Logistic Regression: Categorizes house prices into two classes based on the median price.
  - Random Forest Classifier: Utilizes ensemble learning to classify house prices effectively.

## Results
- **Best performing regression model**: XGBoost with an MAE of 3.03 and R² score of 0.91.
- **Best performing classification model**: Random Forest Classifier with perfect accuracy (1.00) and F1 score (1.00).
- **Performance Metrics**:
  - Linear Regression: MAE of 6.37 and R² score of 0.699.
  - Random Forest Regressor: MAE of 2.73 and R² score of 0.947.
  - Logistic Regression: Accuracy of 0.692 and F1 score of 0.692.

## Contributing
Contributions are welcome! If you would like to contribute to this project, please open an issue or submit a pull request. Make sure to follow the code style and include tests for new features.

## Acknowledgments
- Thanks to the contributors of the libraries used in this project, including scikit-learn, pandas, and XGBoost.
- Acknowledgment to the dataset providers and any individuals or resources that helped during the project.

## Contact
For questions or feedback, please contact rdhadvai@gmu.edu.
```
