# Unicorn Companies EDA Project – Pandas

An Exploratory Data Analysis (EDA) project on global unicorn companies using Python, Pandas, Matplotlib, and Seaborn. This project focuses on understanding unicorn company growth trends, valuation patterns, founding years, and the time companies take to achieve unicorn status.

---

## Project Objective

The objective of this project is to:

- Explore and analyze unicorn company data
- Identify trends and patterns in company growth
- Understand valuation distributions across time intervals
- Analyze how long companies take to achieve unicorn status
- Visualize insights using statistical and graphical methods

---

# Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Quarto (`.qmd`)

---

# Dataset Features

The dataset contains information related to unicorn companies, including:

- Company Name
- Valuation
- Industry
- Country
- Year Founded
- Date Joined
- Investors

---

# Project Workflow

## 1. Data Loading and Exploration

- Loaded dataset using Pandas
- Inspected schema and descriptive statistics
- Checked dataset dimensions and missing values

## 2. Data Cleaning

- Removed null values
- Converted `Date Joined` column to datetime format
- Extracted month and year information from dates
- Calculated the number of years taken to become a unicorn

## 3. Exploratory Data Analysis

Performed analysis on:

- Company founding trends
- Unicorn growth over time
- Monthly unicorn company trends
- Average valuation comparisons
- Quarterly valuation trends
- Time taken to achieve unicorn status

## 4. Data Visualization

Created visualizations using:

- Histograms
- Bar plots
- Box plots
- Grouped bar charts

---

# Key Insights

- Unicorn company growth increased significantly in recent years.
- Companies founded after 2010 generally reached unicorn status faster.
- Valuation trends varied across different quarters and years.
- Certain months showed higher unicorn company activity.
- Outliers exist in the time taken to achieve unicorn status.

---

# Visualizations Included

- Distribution of companies by founding year
- Monthly unicorn growth trends
- Average valuation across quarters
- Distribution of years taken to become unicorns
- Average time to achieve unicorn status

---

# Repository Structure

```text
Unicorn-Companies-EDA/
│
├── Datasets/
│   └── Unicorn_Companies.csv
│
├── notebooks/
│   └── unicorn_companies_eda.qmd
│
├── images/
│
├── outputs/
│   └── unicorn_companies_eda.html
│
├── README.md
└── requirements.txt
```

---

# Installation

Clone the repository:

```bash
git clone https://github.com/your-username/unicorn-companies-eda-pandas.git
```

Install required libraries:

```bash
pip install pandas matplotlib seaborn
```

---

# Running the Project

Open the `.qmd` file in VS Code or Jupyter environment and run the cells sequentially.

To render the Quarto report:

```bash
quarto render unicorn_companies_eda.qmd
```

---

# Future Improvements

- Build interactive dashboards using Power BI or Tableau
- Perform predictive analysis on unicorn valuations
- Add country-wise and industry-wise deep analysis
- Implement machine learning models for valuation prediction

---

# Author

**Udith P Kidiyoor**

Data Analysis | Python | Pandas | Data Visualization
