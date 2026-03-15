# Airbnb Lisbon — Exploratory Data Analysis

## Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on Airbnb listings in Lisbon, Portugal, using real open data from Inside Airbnb. The goal is to uncover pricing patterns, neighbourhood trends, and availability insights that could inform hosting strategy or market analysis.

---

## Dataset

- **Source:** [Inside Airbnb — Lisbon, Portugal](http://insideairbnb.com/get-the-data/)
- **Listings analysed:** 21,613
- **Type:** Public open data

---

## Key Findings

| Metric | Value |
|---|---|
| Total listings analysed | 21,613 |
| Average nightly price | €138.55 |
| Median nightly price | €110.00 |
| Average review score | 4.66 / 5.00 |
| Average availability | 243 days/year |
| Most common room type | Entire home/apt (77.5%) |

### Price Insights
- **Most expensive neighbourhood:** Alguber — significantly above city average
- **Price range:** €9 – €1,000/night (after outlier removal)
- Higher-rated listings do not consistently command higher prices — rating alone is not a price driver

### Availability Insights
- Neighbourhoods like Malveira e São Miguel de Alcaina and Fanhes show the highest availability, suggesting lower demand or more recently listed properties
- Central Lisbon neighbourhoods show lower availability, reflecting higher tourist demand

### Room Type Distribution
- 77.5% of listings are entire homes/apartments
- Shared rooms represent less than 1% of the market

---

## Tools & Skills

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualisation-4C72B0?style=flat)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Charts-orange?style=flat)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-F9AB00?style=flat)

---

## Visualisations

### 1. Average Price by Neighbourhood (Top 15)
Bar chart comparing average nightly prices across the top 15 most expensive neighbourhoods in Lisbon.

### 2. Distribution by Room Type
Pie chart showing the breakdown of listing types — entire home, private room, shared room, hotel room.

### 3. Price vs Review Rating
Scatter plot exploring the relationship between nightly price and guest review scores.

### 4. Average Availability by Neighbourhood (Top 10)
Bar chart showing which neighbourhoods have the highest average availability per year.

---

## Repository Structure

```
📁 airbnb-lisbon-eda
├── 📄 README.md
├── 📓 airbnb_lisbon_eda.ipynb     ← main notebook
├── 📊 price_analysis.png          ← chart exports
└── 📊 ratings_availability.png
```

---

## How to Run

1. Clone this repository
2. Download `listings.csv.gz` from [Inside Airbnb — Lisbon](http://insideairbnb.com/get-the-data/)
3. Open `airbnb_lisbon_eda.ipynb` in Google Colab or Jupyter Notebook
4. Upload the dataset when prompted and run all cells

---

## Academic Context

This project is part of a self-directed data analytics portfolio developed alongside an **MSc in Information Management (Digital Transformation)** at NOVA IMS, Lisbon.

**Author:** Marius Faur · [LinkedIn](https://linkedin.com/in/mariusfaur) · [GitHub](https://github.com/mariussfaur)
