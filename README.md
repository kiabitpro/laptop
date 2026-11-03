
<div align="center">

  <h1>💻 Inside the Laptop Market</h1>
  <h3>Data Cleaning | Feature Engineering | Exploratory Data Analysis</h3>

  <p>
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
    <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
    <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white">
    <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white">
    <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white">
    <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white">
  </p>

  <p>
    <strong>Turning Raw Data into Meaningful Insights.</strong>
  </p>

</div>

---

## 📌 Project Overview

**Inside the Laptop Market** is a Data Analysis project focused on exploring the laptop market through comprehensive data cleaning, feature extraction, feature engineering, and Exploratory Data Analysis (EDA).

The main objective of this project is to transform raw and unstructured laptop data into a clean, organized, and analysis-ready dataset.

Throughout this project, I worked on different real-world data preprocessing challenges, particularly extracting meaningful information from complex columns containing multiple technical specifications.

After completing the data cleaning and feature engineering stages, I performed an extensive EDA to discover patterns, distributions, and relationships between laptop specifications and their prices.

---

## 🎯 Project Objectives

<div align="center">

| # | Objective |
|:---:|---|
| 01 | 🧹 Comprehensive Data Cleaning |
| 02 | 🔍 Missing Values & Duplicate Detection |
| 03 | ⚙️ Feature Extraction |
| 04 | 🛠️ Feature Engineering |
| 05 | 📊 Exploratory Data Analysis |
| 06 | 📈 Data Visualization |
| 07 | 💰 Laptop Price Analysis |

</div>

---

## 📊 Dataset Information

The dataset contains technical specifications and pricing information for different laptop models.

<div align="center">

| Dataset Property | Value |
|:---|:---:|
| Total Records | **1,303** |
| Original Features | **13** |
| Target Feature | **Price_euros** |
| Data Type | Structured Tabular Data |
| Domain | Laptop Market |

</div>

### 📁 Dataset Features

| Feature | Description |
|:---|---|
| Company | Laptop manufacturer |
| Product | Laptop product name |
| TypeName | Laptop category |
| Inches | Screen size |
| ScreenResolution | Screen resolution specifications |
| Cpu | Processor specifications |
| Ram | RAM capacity |
| Memory | Storage specifications |
| Gpu | Graphics processing unit |
| OpSys | Operating system |
| Weight | Laptop weight |
| Price_euros | Laptop price in euros |

---

## 🧹 Data Cleaning & Preprocessing

One of the most important stages of this project was improving the overall quality of the dataset.

I performed several preprocessing operations to make the data consistent, reliable, and suitable for further analysis.

### Key Operations

- Inspecting dataset structure and data types.
- Identifying and handling missing values.
- Detecting duplicate records.
- Identifying inconsistent and noisy data.
- Cleaning text-based columns.
- Converting columns into appropriate data types.
- Extracting information from complex features.
- Creating new features from existing columns.
- Removing unnecessary columns after feature extraction.

---

## ⚙️ Feature Engineering & Extraction

Several original columns contained multiple pieces of information combined into a single feature.

To make the dataset more useful for analysis, I extracted relevant information and transformed these columns into more structured features.

### 🔹 CPU Extraction

Extracting processor brands and relevant specifications from the original CPU column.

### 🔹 GPU Extraction

Separating GPU brands and types to make graphics-related analysis easier.

### 🔹 Memory Extraction

Extracting storage capacities, storage types, and their corresponding units.

### 🔹 Screen Resolution Extraction

Processing screen resolution specifications to obtain more useful display-related features.

### 🔹 RAM Processing

Preparing RAM capacity information for numerical analysis.

### 🔹 Weight Processing

Cleaning and converting laptop weight values into a numerical format.

These transformations improved the interpretability of the dataset and made it easier to perform meaningful analyses.

---

## 📈 Exploratory Data Analysis (EDA)

After completing the preprocessing stage, I performed Exploratory Data Analysis to understand the dataset and investigate different aspects of the laptop market.

The analysis focuses on identifying distributions, comparing categories, and exploring relationships between laptop specifications and prices.

### 01. 🏢 Laptop Manufacturers

- Distribution of laptop brands.
- Number and percentage of laptops produced by each company.
- Comparison of different manufacturers.

### 02. 💻 Laptop Categories

- Distribution of laptop types.
- Analysis of laptop categories based on screen size.
- Comparison of different laptop segments.

### 03. 🖥️ Display Specifications

- Analysis of screen resolutions.
- Distribution of screen sizes.
- Percentage distribution of display specifications.

### 04. ⚙️ Hardware Specifications

- CPU brand distribution.
- GPU brand and type distribution.
- RAM capacity analysis.
- Storage capacity and storage type analysis.

### 05. 🪟 Operating Systems

- Operating system distribution.
- Comparison of operating system categories.

### 06. 💰 Laptop Pricing

- Price distribution across the dataset.
- Price comparison between different laptop categories.
- Exploring relationships between hardware specifications and laptop prices.

---

## 🛠️ Technologies & Libraries

<div align="center">

| Technology | Purpose |
|:---:|---|
| 🐍 Python | Main Programming Language |
| 🐼 Pandas | Data Manipulation & Cleaning |
| 🔢 NumPy | Numerical Operations |
| 📊 Matplotlib | Data Visualization |
| 🎨 Seaborn | Statistical Visualization |
| 📈 Plotly | Interactive Visualizations |
| 📓 Jupyter Notebook | Development Environment |

</div>

---

## 📂 Project Structure

```text
Inside-the-Laptop-Market/
│
├── data/
│   └── laptop_data.csv
│
├── notebooks/
│   └── laptop_analysis.ipynb
│
├── images/
│   └── visualizations/
│
├── README.md
│
└── requirements.txt
```

---

## 🚀 Getting Started

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Inside-the-Laptop-Market.git
```

### 2. Navigate to the Project Directory

```bash
cd Inside-the-Laptop-Market
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Jupyter Notebook

```bash
jupyter notebook
```

Open the project notebook and execute the cells to explore the complete analysis.

---

## 💡 Key Takeaways

This project provided practical experience in working with real-world tabular data and handling challenges commonly encountered during data preprocessing.

Some of the key skills developed throughout this project include:

- Understanding and improving data quality.
- Handling missing, duplicated, and inconsistent data.
- Extracting information from complex features.
- Performing feature engineering.
- Working with numerical and categorical variables.
- Creating informative and interactive visualizations.
- Exploring relationships between technical specifications and market prices.
- Building a structured data analysis workflow.

---

## 🔮 Future Improvements

Potential next steps for this project include:

- Performing deeper statistical analysis.
- Investigating correlations between laptop specifications.
- Developing Machine Learning models for laptop price prediction.
- Building a predictive system to estimate laptop prices based on technical specifications.

---

## 👨‍💻 Author

<div align="center">

  <h3>Kianoush Bishehgar</h3>

  <p>
    Computer Engineering Student
    <br>
    Machine Learning & Data Science Enthusiast
  </p>

  <a href="https://github.com/kiabitpro">
    <img src="https://img.shields.io/badge/GitHub-kiabitpro-181717?style=for-the-badge&logo=github">
  </a>

  <a href="https://www.kaggle.com/kianoshebishegar">
    <img src="https://img.shields.io/badge/Kaggle-Profile-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white">
  </a>

  <a href="https://www.linkedin.com/in/kianoush-bishehgar-4b74b741b/">
    <img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>

</div>

---

<div align="center">

  <h3>⭐ If you find this project useful, consider giving it a star!</h3>

  <p>
    <strong>Explore Data. Discover Patterns. Build Insights.</strong>
  </p>

</div>
