# Oasis Infobyte Data Science Projects

This repository contains a collection of data science and machine learning projects completed as part of the Oasis Infobyte Internship 2025.

## Table of Contents
- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Task Details](#task-details)
- [Datasets](#datasets)
- [Setup & Installation](#setup--installation)
- [How to Run the Notebooks](#how-to-run-the-notebooks)
- [Troubleshooting & Tips](#troubleshooting--tips)
- [Contributing & Extending](#contributing--extending)
- [Requirements](#requirements)
- [Author](#author)

---

## Project Overview

This repository showcases a series of hands-on data science and machine learning tasks, each designed to demonstrate practical skills in data analysis, visualization, and predictive modeling. Every task is self-contained, with its own notebook and dataset, making it easy for readers to explore, learn, and experiment independently.

**Key learning outcomes:**
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Visualization techniques
- Supervised machine learning (classification & regression)
- Model evaluation and comparison
- Real-world dataset handling

Whether you are a beginner or looking to reinforce your skills, these projects provide a step-by-step approach to solving common data science problems.

---

## Project Structure

Each task is organized in its own folder for clarity and modularity:

```
|-- Task_1/
|   |-- Task 1 - Iris Flower Classificaton.ipynb
|   |-- Iris.csv
|
|-- Task_2/
|   |-- Task 2 - Unemployment analysis with python.ipynb
|   |-- Unemployment in India.csv
|   |-- Unemployment_Rate_upto_11_2020.csv
|
|-- Task_3/
|   |-- Task 3-Car Price Prediction.ipynb
|   |-- car data.csv
|
|-- Task_4/
|   |-- Task 4 - EMAIL SPAM DETECTION WITH MACHINE LEARNING.ipynb
|   |-- spam.csv
|
|-- Task_5/
|   |-- Task 5 - Sales Prediction Using Python.ipynb
|   |-- Advertising.csv
|
|-- README.md
|-- requirements.txt
|-- venv/
```

---

## Task Details

### **Task 1: Iris Flower Classification**
- **Objective:** Classify iris flowers into three species (setosa, versicolor, virginica) using their measurements.
- **Skills Demonstrated:**
  - Data exploration and visualization
  - Outlier detection and treatment
  - Label encoding
  - Model training (Logistic Regression, Decision Tree, Random Forest, KNN)
  - Model evaluation and comparison
  - Cross-validation and hyperparameter tuning
- **How to Explore:**
  - Open the notebook in `Task_1/` and run the cells sequentially. Visualizations and model results will appear inline.

### **Task 2: Unemployment Analysis with Python**
- **Objective:** Analyze unemployment rates in India, focusing on trends before and during the COVID-19 pandemic.
- **Skills Demonstrated:**
  - Data cleaning and merging
  - Exploratory data analysis (EDA)
  - Regional and state-wise analysis
  - Correlation and trend visualization
- **How to Explore:**
  - Open the notebook in `Task_2/` and follow the narrative to understand how unemployment data is processed and visualized.

### **Task 3: Car Price Prediction**
- **Objective:** Predict the selling price of cars based on features like brand, year, fuel type, and more.
- **Skills Demonstrated:**
  - Data cleaning and encoding
  - Feature engineering
  - Regression modeling (Linear, Lasso)
  - Model evaluation (R2 score, RMSE)
- **How to Explore:**
  - Open the notebook in `Task_3/` and experiment with different models or features to see their impact on price prediction.

### **Task 4: Email Spam Detection with Machine Learning**
- **Objective:** Build a machine learning model to classify emails as spam or not spam.
- **Skills Demonstrated:**
  - Text data preprocessing
  - Feature extraction with TF-IDF
  - Logistic Regression for classification
  - Model evaluation (accuracy, classification report)
- **How to Explore:**
  - Open the notebook in `Task_4/` and try modifying the preprocessing steps or model parameters for better results.

### **Task 5: Sales Prediction Using Python**
- **Objective:** Predict product sales based on advertising spend across TV, radio, and newspaper.
- **Skills Demonstrated:**
  - Data cleaning and EDA
  - Feature selection
  - Linear Regression modeling
  - Model evaluation (MSE, RMSE, R2 score)
- **How to Explore:**
  - Open the notebook in `Task_5/` and analyze how different advertising channels affect sales.

---

## Datasets
- Each dataset is located inside its respective `Task_{Task No}` folder alongside the corresponding notebook.
- All notebooks are set up to read their data from the same folder, so you do not need to change any file paths if you run the notebook from within its folder.

---

## Setup & Installation

**Follow these steps to set up your environment and run the projects:**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/aaryan-paliwal/OIS-SIP-Machine-Learning.git
   ```
2. **Create and activate a virtual environment (recommended):**
   ```bash
   python -m venv venv
   venv\Scripts\Activate.ps1  # On Windows
   # or
   source venv/bin/activate  # On macOS/Linux
   ```
3. **Install required packages:**
   ```bash
   pip install -r requirements.txt
   ```

---

## How to Run the Notebooks

1. **Navigate to the desired task folder:**
   ```bash
   cd Task_1  # or Task_2, Task_3, etc.
   ```
2. **Start Jupyter Notebook or JupyterLab:**
   ```bash
   jupyter notebook
   # or
   jupyter lab
   ```
3. **Open the notebook file in your browser and run the cells sequentially.**
   - All file paths in the notebooks assume the CSV is in the same folder as the notebook.
   - Outputs, plots, and results will appear as you run each cell.
  
---

## Troubleshooting & Tips

- **Missing Packages:** If you get an `ImportError`, make sure you have activated your virtual environment and installed all requirements.
- **File Not Found:** Ensure you are running the notebook from within the correct `Task_{Task No}` folder so that relative file paths work.
- **Kernel Issues:** If the notebook kernel fails to start, restart Jupyter Notebook or JupyterLab, and ensure your virtual environment is active.
- **Custom Experiments:** Feel free to duplicate notebooks and try your own data, models, or visualizations!
- **Updating Requirements:** If you add new packages, update `requirements.txt` with `pip freeze > requirements.txt`.

---

## Contributing & Extending

- **Fork this repository** to your own GitHub account to experiment or build on these projects.
- **Pull requests** are welcome if you want to contribute improvements or new tasks.
- **Ideas for extension:**
  - Try different machine learning models or feature engineering techniques.
  - Add more visualizations or interactive widgets.
  - Use additional datasets for more complex analysis.

---

## Requirements
- Python 3.7+
- Jupyter Notebook or JupyterLab
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install all requirements with:
```bash
pip install -r requirements.txt
```

---

## Author
- **Aaryan Paliwal**

---

Feel free to explore each notebook for detailed code, analysis, and results. If you have questions or suggestions, open an issue or reach out!
