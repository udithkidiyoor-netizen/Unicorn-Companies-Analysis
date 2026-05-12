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

- According to data analysis that was conducted on a dataset of 1074 unicorn companies, companies that joined in the months of September and October tended to take less time to become unicorns.
- Another finding was that many of the unicorn companies that were founded in 2021 were founded in the United States and belong to "Fintech", "E-commerce & direct-to-consumer", and "Internet software & services" industries. So if the stakeholders want to invest in companies founded in 2021, it would be a good idea to consider companies that belong to these industries, as they may be strong candidates for becoming unicorns.
- It was also discovered that the average valuation of companies that joined in 2021 is highest in the first quarter of the year, and the average valuation of companies that joined in 2020 is the third quarter of the year. When considering companies that newly join in the future, it would be worth closely looking at companies that join in the first and third quarters of the year.
- The data can be analyzed further to gather more insights that are specific to the interests of the investing firm and the stakeholders.

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
