# Software-effort-estimation-using-machine-learning-technique

  [![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/)
  [![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Overview
This project implements **Software Effort Estimation** using various machine learning regression techniques. The goal is to predict key project metrics such as working time, days required, and total working days based on task characteristics and historical data.
     9	
    10	## 📋 Project Description
    11	
    12	Accurate software effort estimation is crucial for project planning and resource allocation. This repository demonstrates the application of machine learning algorithms to predict:
    13	- **Total Working Time (in hours)**
    14	- **Days Required**
    15	- **Total Working Days**
    16	
    17	## 🎯 Features
    18	
    19	- **Data Preprocessing**: Label encoding for categorical variables
    20	- **Multiple ML Models**:
    21	  - Decision Tree Regressor
    22	  - K-Nearest Neighbors (KNN) Regressor
    23	  - Support Vector Regression (SVR)
    24	- **Model Evaluation**: MAE, MSE, and R² score metrics
    25	- **Visualization**: Comparison of actual vs predicted values
    26	
    27	## 📊 Dataset
    28	
    29	The project uses the **TMS_Data.xlsx** dataset containing the following features:
    30	
    31	| Feature | Description |
    32	|---------|-------------|
    33	| UserId | Unique identifier for users |
    34	| TaskHistoryId | Task history identifier |
    35	| ProjectId | Project identifier |
    36	| ClientId | Client identifier |
    37	| TypeName | Type of task (categorical) |
    38	| TaskOverallState | Current state of task (categorical) |
    39	| PriorityName | Priority level (categorical) |
    40	| TotalWorkingTimeInHour | **Target**: Total working time in hours |
    41	| NoOfStart | Number of start events |
    42	| NoOfPause | Number of pause events |
    43	| NoOfFinish | Number of finish events |
    44	| DaysRequired | **Target**: Days required for completion |
    45	| TotalWorkingDay | **Target**: Total working days |
    46	
    47	## 🛠️ Technologies Used
    48	
    49	- **Python 3.7+**
    50	- **pandas** - Data manipulation
    51	- **NumPy** - Numerical computations
    52	- **scikit-learn** - Machine learning algorithms
    53	- **Matplotlib** - Data visualization
    54	
    55	## 📦 Installation
    56	
    57	1. Clone the repository:
    58	```bash
    59	git clone <repository-url>
    60	cd <repository-directory>
    61	```
    62	
    63	2. Install required dependencies:
    64	```bash
    65	pip install pandas numpy scikit-learn matplotlib openpyxl
    66	```
    67	
    68	## 🚀 Usage
    69	
    70	1. Open the Jupyter notebook:
    71	```bash
    72	jupyter notebook "Software effort estimation.ipynb"
    73	```
    74	
    75	2. Run all cells sequentially to:
    76	   - Load and preprocess the data
    77	   - Train the machine learning models
    78	   - Evaluate model performance
    79	   - Visualize results
    80	
    81	## 📈 Model Performance
    82	
    83	The models are evaluated using the following metrics:
    84	- **MAE (Mean Absolute Error)**: Average absolute difference between predicted and actual values
    85	- **MSE (Mean Squared Error)**: Average squared difference between predicted and actual values
    86	- **R² Score**: Coefficient of determination indicating model fit quality
    87	
    88	## 📁 File Structure
    89	
    90	```
    91	├── README.md                           # Project documentation
    92	├── Software effort estimation.ipynb    # Main Jupyter notebook
    93	└── TMS_Data.xlsx                       # Dataset file
    94	```
    95	
    96	## 🔍 Methodology
    97	
    98	1. **Data Loading**: Import Excel dataset using pandas
    99	2. **Preprocessing**: 
   100	   - Encode categorical variables (TypeName, TaskOverallState, PriorityName)
   101	   - Feature selection
   102	3. **Train-Test Split**: 90% training, 10% testing
   103	4. **Model Training**: Fit multiple regression models
   104	5. **Evaluation**: Compare predictions against actual values
   105	6. **Visualization**: Plot actual vs predicted values
   106	
   107	## 📝 Results
   108	
   109	The project demonstrates the feasibility of using machine learning for software effort estimation. Different models can be compared to find the best performing algorithm for the given dataset.
   110	
   111	## 🤝 Contributing
   112	
   113	Contributions are welcome! Please feel free to submit a Pull Request.
   114	
   115	## 📄 License
   116	
   117	This project is licensed under the MIT License.
   118	
   119	## 👨‍💻 Author
   120	
   121	*Add your name and contact information here*
   122	
   123	## 🙏 Acknowledgments
   124	
   - scikit-learn team for excellent ML libraries
   - pandas development team for data manipulation tools
   - Jupyter project for interactive computing environment
   128	
   129	---
   130	
