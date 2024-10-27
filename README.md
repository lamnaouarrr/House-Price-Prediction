# Project Title
**House Prices - Advanced Regression Techniques**

---

## Outline

- [Description](#description)
  - [Overview](#overview)
  - [Objectives](#objectives)
  - [Conclusion](#conclusion)
- [Dataset](#dataset)
  - [Dataset Source](#dataset-source)
  - [License](#license)
- [Installation](#installation)
  - [Prerequisites](#prerequisites)
  - [Clone the Repository](#clone-the-repository)
  - [Create a Virtual Environment](#create-a-virtual-environment-optional)
  - [Install Required Packages](#install-required-packages)
  - [Download the Dataset](#download-the-dataset)
  - [Run the Jupyter Notebook](#run-the-jupyter-notebook)
- [Usage](#usage)
  - [Running the Notebook](#running-the-notebook)
  - [Example Usage](#example-usage)
- [Results](#results)
  - [Model Performance](#model-performance)
  - [Key Insights](#key-insights)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

---

## Description

### Overview

This project is based on the Kaggle competition "House Prices - Advanced Regression Techniques." The goal is to predict house prices using a dataset with 79 explanatory variables describing various aspects of residential homes in Ames, Iowa. By experimenting with multiple regression techniques, the project aims to achieve a robust prediction model for house prices.

### Objectives

The main goals of this project are to:

- **Data Exploration and Preprocessing:** Analyze the dataset, handle missing values, and prepare the data for model training through encoding and scaling.
- **Model Development:** Implement various regression techniques, such as Linear Regression, SVM, Decision Trees, and advanced ensemble methods like Random Forests, Gradient Boosting, and CatBoost.
- **Model Evaluation:** Evaluate models using the Root-Mean-Squared-Error (RMSE) metric and perform hyperparameter tuning to improve accuracy.
- **Feature Engineering:** Enhance model performance by reducing multicollinearity through feature selection and transformation.
- **Documentation and Sharing:** Share the project with clear documentation for reproducibility and further use.

### Conclusion

This project demonstrates a comprehensive machine learning approach for predicting house prices, covering data preprocessing, model development, and performance evaluation. The insights gained offer valuable understanding into the factors influencing real estate prices.

---

## Dataset

The dataset used for this project is sourced from Kaggle's "House Prices - Advanced Regression Techniques" competition. You can find the dataset [here](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data).

### License

The dataset is licensed under the MIT License, which allows for use, sharing, and modification with appropriate credit. Full license text is available [here](https://www.mit.edu/~amini/LICENSE.md).

---

## Installation

To get started with the project, follow the steps below to set up the environment and dependencies:

### Prerequisites

Ensure Python 3.6 or higher is installed. Download it from the [official website](https://www.python.org/downloads/).

### Step 1: Clone the Repository

Clone this repository to your local machine using the command below:

```bash
git clone https://github.com/yourusername/house-prices-advanced-regression.git
```

Replace `yourusername` with your actual GitHub username.

### Step 2: Create a Virtual Environment (Optional)

Create a virtual environment using venv to isolate dependencies:

```bash
cd house-prices-advanced-regression
python -m venv venv
```

Activate the virtual environment:

- **For Windows:**

  ```bash
  venv\Scripts\activate
  ```

- **For macOS/Linux:**

  ```bash
  source venv/bin/activate
  ```

### Step 3: Install Required Packages

Run the following command to install the necessary dependencies:

```bash
pip install -r requirements.txt
```

The `requirements.txt` file may include:

```
numpy
pandas
scikit-learn
matplotlib
seaborn
jupyter
xgboost
lightgbm
catboost
```

### Step 4: Download the Dataset

You can download the dataset from the Kaggle competition page and place it in a `data/` folder within your project directory.

### Step 5: Run the Jupyter Notebook

Launch Jupyter Notebook with the following command:

```bash
jupyter notebook
```

---

## Usage

### Running the Notebook

To run the notebook, follow these steps:
1. Download the dataset and place it in the appropriate directory.
2. Open the notebook and run the cells step-by-step to preprocess the data, build models, and evaluate results.

---

## Results

### Model Performance

The table below summarizes the performance of different models used in this project, focusing on the CatBoost model as the best-performing one. The primary evaluation metric is RMSE (Root Mean Squared Error), with lower scores indicating better performance.

| Model                  | Techniques Used                           | RMSE Score   |
|------------------------|-------------------------------------------|--------------|
| Linear Regression      | Baseline                                  | 0.16589      |
| Support Vector Machine | Regularization, Feature Engineering       | 0.15336      |
| Decision Tree          | Hyperparameter Tuning                     | 0.18508      |
| **Tree Ensembles (CatBoost)** | **Best Model** – Tuning & Engineering | **0.12717** |

The best performance was achieved using **Tree Ensembles with CatBoost**, resulting in an RMSE score of **0.12717**, demonstrating its effectiveness in capturing complex patterns in the data. This is a significant improvement from the initial baseline score of **0.16589** with linear regression.

You can view my progress and submissions on [my Kaggle profile](https://www.kaggle.com/lamnaouarrr/competitions).


## Contributing

Feel free to fork this repository and submit pull requests to contribute! Make sure to follow contribution guidelines, such as creating clear commit messages and submitting well-documented code.

---

## Acknowledgements

This project is based on the Kaggle competition "House Prices - Advanced Regression Techniques." Special thanks to Dean De Cock for compiling the Ames Housing dataset used for this competition.

---

## Contact

For any questions or inquiries, you can contact the project maintainer at:  
**Email:** ayoublamnaouar1@gmail.com  
**GitHub:** [lamnaouarrr](https://github.com/lamnaouarrr)  
**LinkedIn:** [Ayoub Lamnaouar](https://www.linkedin.com/in/ayoub-lamnaouar-80730317a/)  
