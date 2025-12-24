# Fragrance Data Cleaning

This project demonstrates end-to-end data cleaning in Python.  
The goal is to transform raw fragrance product data into a clean, structured, analysis-ready dataset.

## 📦 Dataset Overview

**Raw size:** ~70,000 fragrance records  
**Final output:** Cleaned dataset with structured scent profiles and normalized attributes

### Final Dataset Columns

| Column | Description |
|------|------------|
Name | Clean fragrance name |
Gender | (Women / Men / Unisex) |
Rating Value | Average user rating |
Rating Count | Number of ratings |
Top Notes | Extracted top scent notes |
Middle Notes | Extracted middle scent notes |
Base Notes | Extracted base scent notes |
url | Source product page |

## 🧹 Cleaning & Feature Engineering Steps

- Audited missing values and data types
- Normalized gender categories (Women / Men / Unisex)
- Removed duplicate products
- Filtered out unrated fragrances to retain meaningful user data
- Extracted and standardized **Top, Middle, and Base Notes** from raw text descriptions
- Removed redundant and non-informative columns
- Reordered columns
- Exported final dataset for analysis

## 🧪 Tools & Technologies

- Python
- pandas
- NumPy
- Jupyter Notebook
- Git & GitHub


## 📁 Project Structure

├── .venv/                     # Local Python environment (ignored by Git)
├── data/
│   ├── raw/
│   │   └── fra_perfumes.csv   # Original dataset
│   └── processed/
│       └── cleaned_fragrances.csv  # Final cleaned dataset
├── notebooks/
│   ├── 01_data_audit.ipynb
│   └── 02_cleaning_pipeline.ipynb
├── reports/
├── src/
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt

## 📈 Outcome

The final dataset is a fully normalized, analysis ready for:
- market analysis
- product trend modeling
- recommendation systems
- exploratory data analysis

## 👤 Author
Miguel Gutierrez