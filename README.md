# Software-effort-estimation-using-machine-learning-technique
- **[Software effort estimation using machine learning technique](https://dspace.uevora.pt/rdpc/bitstream/10174/41184/1/Paper_91-Software_Effort_Estimation_using_Machine_Learning_Technique.pdf)** - SAI, 2023

  [![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/)
  [![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
## Publication Link --> 
## Overview
**Software Engineering Effort Estimation** plays a significant role in managing project cost, quality, and time and creating software. Researchers have been paying close attention to software estimation during the past few decades, and a great amount of work has been done utilizing a variety of machine-learning techniques and algorithms. In order to better effectively evaluate predictions, this study recommends various machine learning algorithms for estimating, including k-nearest neighbor regression, support vector regression, and decision trees. These methods are now used by the software development industry for software estimating with the goal of overcoming the limitations of parametric and conventional estimation techniques and advancing projects. Our dataset, which was created by a software company called Edusoft Consulted LTD, was used to assess the effectiveness of the established method. The three commonly used performance evaluation measures, mean absolute error (MAE), mean squared error (MSE), and R square error, represent the base for these. Comparative experimental results demonstrate that decision trees perform better at predicting effort than other techniques.

## 🎯 Features
- **Data Preprocessing**: Label encoding for categorical variables
- **Multiple ML Models**:
- Decision Tree Regressor
- K-Nearest Neighbors (KNN) Regressor
- Support Vector Regression (SVR)
- **Model Evaluation**: MAE, MSE, and R² score metrics
- **Visualization**: Comparison of actual vs predicted values

## 📊 Dataset
The project uses the **TMS_Data.xlsx** dataset containing the following features:
| Feature | Description |
|---------|-------------|
| UserId | Unique identifier for users |
| TaskHistoryId | Task history identifier |
| ProjectId | Project identifier |
| ClientId | Client identifier |
| TypeName | Type of task (categorical) |
| TaskOverallState | Current state of task (categorical) |
| PriorityName | Priority level (categorical) |
| TotalWorkingTimeInHour | **Target**: Total working time in hours |
| NoOfStart | Number of start events |
| NoOfPause | Number of pause events |
| NoOfFinish | Number of finish events |
| DaysRequired | **Target**: Days required for completion |
| TotalWorkingDay | **Target**: Total working days |

## 🛠️ Technologies Used
- **Python 3.7+**
- **pandas** - Data manipulation
- **NumPy** - Numerical computations
    52	- **scikit-learn** - Machine learning algorithms
    53	- **Matplotlib** - Data visualization


## 📁 File Structure
├── README.md                           # Project documentation
├── Software effort estimation.ipynb    # Main Jupyter notebook
└── TMS_Data.xlsx                       # Dataset file


## 🔍 Methodology
1. **Data Loading**: Import Excel dataset using pandas
2. **Preprocessing**: 
- Encode categorical variables (TypeName, TaskOverallState, PriorityName)
- Feature selection
3. **Train-Test Split**: 90% training, 10% testing
4. **Model Training**: Fit multiple regression models
5. **Evaluation**: Compare predictions against actual values
6. **Visualization**: Plot actual vs predicted values
 
