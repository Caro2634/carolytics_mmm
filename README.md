# Marketing Mix Modeling (MMM) – Demo Project

This project demonstrates an end-to-end Marketing Mix Modeling (MMM) workflow implemented in Python.
It is designed as a lightweight, interpretable example of how data science can support marketing
budget allocation and strategic decision-making.

## What this project does
- Loads synthetic marketing and sales data
- Fits a regression-based Marketing Mix Model
- Estimates the marginal impact of marketing channels on sales
- Interprets results from a business perspective

## Dataset
The dataset is fully synthetic and created for demonstration purposes.
It includes weekly data on:
- TV, Search, and Social spend
- Pricing and promotions
- Competitor activity
- Sales

## Project structure
- `data/dummy_data.csv` – synthetic dataset
- `notebooks/mmm_model.ipynb` – main MMM analysis
- `src/model.py` – optional script placeholder
- `requirements.txt` – dependencies

## How to run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/mmm_model.ipynb
