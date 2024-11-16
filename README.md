
# Customer Segmentation Project

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.x-lightblue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.x-orange)

## Overview

This project focuses on **Customer Segmentation**, a vital aspect of marketing analytics. The analysis includes **Exploratory Data Analysis (EDA)**, **RFM Analysis**, and **Market Basket Analysis using the Apriori algorithm**. These techniques help uncover customer patterns, segment customers into meaningful groups, and analyze their purchasing behavior for targeted strategies.

---

## Features

- **Exploratory Data Analysis (EDA)**: Uncover patterns, trends, and insights from the dataset.
- **RFM Analysis**: Recency, Frequency, and Monetary analysis for customer segmentation.
- **Market Basket Analysis**: Use the Apriori algorithm to identify itemsets and generate association rules.
- **Multi-Layer Data Storage**: Organized into Bronze and Gold layers for raw and processed data.
- **Interactive Notebooks**: Jupyter notebooks for reproducible and detailed analysis.

---

## Folder Structure

```
Customer_Segmentation_Project/
├── Data/
│   ├── Bronze Layer/         # Raw data files
│   │   └── data.csv
│   ├── Gold Layer/           # Processed data files
│       └── uk_data.csv
├── Project Files/
│   ├── 1. cleanDataSet.ipynb # Data cleaning and preprocessing
│   ├── 2. RFM Modelling.ipynb# RFM analysis
│   ├── 3. Market_basket_analysis.ipynb # Market basket analysis
├── README.md                 # Project documentation
```

---

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/hiteshg1318/Customer_Segmentation_Project.git
   cd Customer_Segmentation_Project
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up your dataset**
   - Place raw datasets in the `Bronze Layer` folder.
   - Processed datasets will be stored in the `Gold Layer` folder after cleaning.

---

## Analysis Steps

### 1. Data Cleaning and Preprocessing
Run the notebook `1. cleanDataSet.ipynb` to:
- Clean raw data (`data.csv`) in the Bronze Layer.
- Generate processed data (`uk_data.csv`) stored in the Gold Layer.

### 2. RFM Analysis
Open the `2. RFM Modelling.ipynb` notebook to:
- Perform Recency, Frequency, and Monetary value analysis.
- Identify customer segments based on purchasing behavior.

### 3. Market Basket Analysis
Use the `3. Market_basket_analysis.ipynb` notebook to:
- Identify frequent itemsets using the Apriori algorithm.
- Generate association rules to understand product relationships.

---


## Contributing

We welcome contributions! Follow these steps:

1. Fork the repository.
2. Create a branch: `git checkout -b feature-branch`.
3. Commit your changes: `git commit -m 'Add a feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Open a pull request.

---


## Contact

For any queries or suggestions, feel free to reach out:

- **Author**: Hitesh Gupta  
- **Email**: hitesh.gupta@example.com  
- **GitHub**: [Hitesh Gupta](https://github.com/hiteshg1318)

---

## Acknowledgments

- [Pandas Documentation](https://pandas.pydata.org/)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Apriori Algorithm](https://en.wikipedia.org/wiki/Apriori_algorithm)
