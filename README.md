# Data Visualization in Python

## Overview

This project is a group research work for **MTH1203 – Probability and Statistics**, part of the **Bachelor of Science in Information Technology (BSIT), Year 1, Semester 2** at **Uganda Christian University**.

It explores how data can be represented graphically using Python libraries, turning raw numbers into clear, meaningful visuals that reveal patterns, trends, and relationships. The project is implemented in a Jupyter notebook using the built-in **Tips** dataset from Seaborn.

---

## Objectives

- Understand the role of data visualization in statistics and data analysis.
- Learn how to use Python libraries to create different types of charts.
- Apply best practices in data visualization.
- Produce clear, honest, and informative visualizations from real data.

---

## Python Libraries Used

| Library | Purpose |
|--------|---------|
| **Matplotlib** | Foundational plotting library for bar, line, histogram, and scatter plots |
| **Seaborn** | High-level statistical visualization (box plots, heatmaps, etc.) |
| **Plotly** | Interactive charts with hover, zoom, and pan |
| **Pandas** | Loading, organising, and inspecting data |

---

## Dataset

We used the **Tips dataset**, which comes built into Seaborn. It records restaurant bills, tips, and customer details.

**Key columns:**

- `total_bill` – the bill amount
- `tip` – the tip given
- `day` – day of the week
- `smoker` – whether the customer was a smoker
- `size` – number of people at the table

---

## Types of Plots Implemented

| Plot | Purpose |
|------|---------|
| **Bar Chart** | Compare average tip across days |
| **Line Chart** | Show total bill across the first 50 records |
| **Histogram** | Show distribution of total bill amounts |
| **Scatter Plot** | Show relationship between total bill and tip |
| **Box Plot** | Compare total bill across days and detect outliers |
| **Pie Chart** | Show smoker vs non-smoker proportions |
| **Heatmap** | Correlation between total bill, tip, and party size |
| **Interactive Plotly Scatter** | Explore total bill vs tip with hover and zoom |

---

## Best Practices Followed

1. **Choose the correct chart** for the data and question.
2. **Use clear titles** for every plot.
3. **Label the x-axis and y-axis** with units where necessary.
4. **Keep charts simple** and avoid unnecessary information.
5. **Use colour sensibly** to encode information, not decorate.
6. **Be honest** – no truncated axes or misleading scales.
7. **Ensure accessibility** – readable fonts and colour-blind friendly palettes.

---

## Notebook Structure

The Jupyter notebook (`group1_work.ipynb`) is organised as follows:

1. Import libraries
2. Load and inspect the dataset
3. Bar chart – average tip by day
4. Line chart – total bill for first 50 records
5. Histogram – distribution of total bill
6. Scatter plot – total bill vs tip
7. Box plot – total bill by day
8. Pie chart – smokers and non-smokers
9. Heatmap – correlation matrix
10. Interactive Plotly chart – total bill vs tip

Each plot includes a title, axis labels, and a sensible colour scheme.

---

## Key Findings

- **Total bill and tip** are closely related – bigger bills tend to get bigger tips.
- **Sunday** has the highest average tip.
- **Most customers are non-smokers** (~62%).
- **Saturday and Sunday** have higher bills and more outliers.

---

## Files

| File | Description |
|------|-------------|
| `group1_work.ipynb` | Jupyter notebook with all plots and code |
| `visualisation.pdf` | Full research report |
| `Data Visualization Presentation.pptx` | Presentation slides |

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/data-visualization-python.git
   cd data-visualization-python
