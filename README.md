# Assignment 1: Data Profiling (EDA) Report

**Group 5 (T6) – E-Commerce / Retail**

| Name | Matric No. |
|---|---|
| HAZIQ NUR IMAN BIN MOHD RIZAL (Leader) | A210506 |
| MUHAMMAD RAZEEN REDHA BIN MOHAMAD RIDZUAN | A210729 |
| MOHAMMAD SADIQ BIN SAHROM | A209866 |
| WAN FAHIYM HUZEN BIN WAN HAFIZUDDIN | A209886 |

## Scenario

An online retail company receives thousands of customer reviews every day and wants to automatically classify customer complaints by product category and sentiment. In this notebook we profile a real review dataset, fix its data quality problems, and check PII and bias risks.

## Data source

- Women's E-Commerce Clothing Reviews (Kaggle)
- https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews
- Downloaded as a CSV and saved in `data/womens_clothing_ecommerce_reviews.csv`

## Files

- `EDA_Data_Profiling.ipynb` – the notebook
- `data/womens_clothing_ecommerce_reviews.csv` – raw data
- `requirements.txt` – libraries needed

## How to run

1. Download or clone this repository.
2. Install the libraries:
   ```
   pip install -r requirements.txt
   ```
3. Open `EDA_Data_Profiling.ipynb` in Jupyter Notebook.
4. Click **Kernel → Restart & Run All**.

The notebook runs from top to bottom and saves the cleaned data as `data/cleaned_reviews.csv`.
