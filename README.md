📊 Rossmann Store Sales Prediction

🔍 Overview

This project is focused on predicting sales for Rossmann stores using historical sales data. The dataset is sourced from Kaggle's "Rossmann Store Sales" competition.

📂 Dataset

The dataset includes:

📄 train.csv: Historical sales data for training.

📄 test.csv: Data for making predictions.

🏬 store.csv: Information about different stores.

📄 sample_submission.csv: Template for submitting predictions.

🛠 Dependencies

To run this project, install the required dependencies:

pip install numpy pandas matplotlib seaborn opendatasets xgboost lightgbm scikit-learn graphviz --quiet

🚀 Getting Started

Clone this repository:

git clone <repository_url>
cd <repository>

Download the dataset:

import opendatasets as od
od.download('https://www.kaggle.com/competitions/rossmann-store-sales')

Load the dataset in your Jupyter Notebook:

import pandas as pd
train_df = pd.read_csv('rossmann-store-sales/train.csv')
test_df = pd.read_csv('rossmann-store-sales/test.csv')
store_df = pd.read_csv('rossmann-store-sales/store.csv')

📌 Project Structure

📜 notebook.ipynb: Jupyter Notebook with data analysis and model training.

📄 requirements.txt: List of dependencies.

📖 README.md: Project documentation.

📜 License

This project is for educational purposes and follows Kaggle's dataset usage rules.
