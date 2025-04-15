# Data Preparation for Travel Time Prediction

This repository contains a Jupyter Notebook for preprocessing and preparing travel time data for use in machine learning models. The primary goal is to clean, explore, and structure the data for optimal model training and evaluation.

## 📁 File Structure

- `Data_preparation.ipynb`: Jupyter notebook containing the full data preprocessing workflow.
- `travel_times.csv`: Dataset used for analysis 

## 🚀 Features

- Exploratory Data Analysis (EDA) using `matplotlib` and `seaborn`
- Data cleaning: handling missing values, inspecting data types, etc.
- Automated machine learning setup using [FLAML](https://github.com/microsoft/FLAML)
- Preparation of features for modeling

## 📦 Requirements

- Python 3.8+
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `flaml`



## 📊 Dataset

The notebook expects a CSV file named `travel_times.csv` with travel-related features. The structure and columns of the dataset are explored in the notebook using `.info()` and other EDA techniques.

## 🧠 AutoML Integration

This project uses FLAML to demonstrate quick and efficient model selection and training for travel time prediction.

## 📈 Outputs

- Cleaned and processed dataset ready for model training
- Visualizations showing data distributions, correlations, and missing value patterns
- Example model performance from AutoML training

## 🛠️ Usage

Clone the repository:

```bash
git clone https://github.com/shantiarashidy/travel-time-data-prep.git
cd travel-time-data-prep
```

Open the notebook:

```bash
jupyter notebook Data_preparation.ipynb
```

## 🙌 Contributing

Feel free to fork the repo, open issues, or submit pull requests.

## 📄 License

MIT License
