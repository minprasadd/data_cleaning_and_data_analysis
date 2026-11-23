# 🇳🇵 Nepal Household Survey — Data Science Project

## 📌 Project Overview

The **Nepal Household Survey Data Science Project** focuses on cleaning, analyzing, and visualizing household survey data to explore demographic, socioeconomic, and digital-access characteristics of respondents in Nepal.

The project uses Python-based data analysis techniques to prepare raw survey data, handle missing values, explore patterns, and present findings through statistical summaries and visualizations.

The project concludes with a dashboard that brings together important indicators related to household size, monthly income, land ownership, remittance, and digital connectivity.

## 🎯 Project Objectives

* Clean and prepare raw household survey data for analysis.
* Identify and handle missing values using appropriate techniques.
* Explore demographic and socioeconomic characteristics of respondents.
* Analyze differences in household and income-related variables across provinces.
* Examine digital access, including electricity, internet, and mobile phone usage.
* Create meaningful visualizations to communicate findings.
* Develop a statistical dashboard summarizing key indicators.

## 📂 Project Structure

```text
Nepal-Survey-Data-Science/
│
├── data/
│   ├── nepal_survey_messy.csv
│   └── nepal_survey_cleaned.csv
│
├── notebooks/
│   └── nepal_survey_analysis.ipynb
│
├── dashboard/
│   └── nepal_household_dashboard.png
│
├── README.md
└── requirements.txt
```

*Note: The structure above is a suggested organization. Include only the files and folders you actually upload. The dashboard image can be saved separately if you want to display it directly in your README.*

## 🛠️ Technologies and Libraries

The project uses the following tools and Python libraries:

* **Python** — primary programming language.
* **Pandas** — data manipulation, cleaning, and analysis.
* **NumPy** — numerical operations.
* **Matplotlib** — data visualization.
* **Seaborn** — statistical visualizations and heatmaps.
* **Jupyter Notebook** — interactive data analysis and documentation.

## 🧹 Data Cleaning

The first stage focuses on improving the quality and consistency of the raw survey dataset.

The following operations are performed:

* Inspecting dataset dimensions, column names, and data types.
* Identifying missing values and calculating their percentages.
* Creating a working copy while preserving the original dataset.
* Removing selected columns with excessive missing values.
* Handling missing numerical values using mean and median imputation.
* Handling missing categorical values using mode imputation.
* Applying forward fill and backward fill to selected categorical columns.
* Validating the cleaned dataset and checking for remaining missing values.
* Comparing the original and cleaned datasets.
* Exporting the cleaned data to a new CSV file.

The cleaned dataset is then used for exploratory data analysis.

## 📊 Exploratory Data Analysis (EDA)

Exploratory Data Analysis is performed to understand the characteristics and distributions of the survey variables.

The analysis covers several areas:

### 1. Demographic Analysis

* Age distribution.
* Gender-related exploration.
* Household size.
* Respondent distribution across provinces and districts.

### 2. Socioeconomic Analysis

* Monthly household income.
* Land ownership measured in Ropani.
* Annual remittance.
* Occupation and education levels.

### 3. Digital Access Analysis

* Mobile phone usage.
* Electricity access.
* Internet access.
* Internet access comparisons across provinces.

### 4. Statistical Analysis

* Descriptive statistics.
* Frequency distributions.
* Average household size by province.
* Monthly income distribution.
* Relationships between selected numerical variables.

## 📈 Data Visualization

Multiple visualization techniques are used to explore and communicate patterns in the data.

These include:

* **Bar Charts** — comparing respondent counts and selected variables.
* **Pie Charts** — examining the distribution of respondents across provinces and districts.
* **Histograms** — exploring numerical distributions, particularly monthly income.
* **Line Plots** — comparing average household size across provinces.
* **Box Plots** — examining income distributions and mobile phone usage across selected groups.
* **Scatter Plots** — exploring age and gender variables.
* **Missing-Value Heatmaps** — visualizing missing data before and after cleaning.
* **Correlation Heatmaps** — examining correlations between selected numerical variables.

## 📊 Summary Dashboard

The project includes a dashboard titled **Nepal Household & Socioeconomic Analysis Report**.

The dashboard combines six visualizations:

1. Average household size by province.
2. Average monthly income by province.
3. Monthly income distribution.
4. Monthly income by internet access.
5. Internet access by province.
6. Correlation heatmap of selected numerical variables.

The dashboard is accompanied by a statistical summary containing key indicators, including:

* Total respondents analyzed.
* Average monthly income.
* Average household size.
* Average land ownership.
* Average annual remittance.
* Most common occupation.
* Most common education level.
* Electricity access percentage.
* Internet access percentage.

## 🔍 Key Findings

Based on the 200 respondents analyzed in the notebook, the statistical summary reports the following results:

| Indicator                   |         Result |
| --------------------------- | -------------: |
| Total respondents           |            200 |
| Average monthly income      |  NPR 73,582.50 |
| Average household size      |   5.64 members |
| Average land ownership      |    9.41 Ropani |
| Average annual remittance   | NPR 255,100.28 |
| Most common occupation      |     Daily Wage |
| Most common education level |            SLC |
| Electricity access          |          48.0% |
| Internet access             |          45.5% |

These results describe the dataset analyzed in this project. They should not be interpreted as nationally representative estimates for Nepal without information about the survey's sampling methodology and representativeness.

## 🚀 Getting Started

### Prerequisites

Install Python and Jupyter Notebook, or use Visual Studio Code with its Python and Jupyter extensions.

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace the placeholder with your actual GitHub repository URL.

### 2. Navigate to the Project Directory

```bash
cd Nepal-Survey-Data-Science
```

### 3. Install the Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Notebook

Open the notebook in Jupyter Notebook or Visual Studio Code and execute the cells in order.

**Important:** Update the dataset file paths in the notebook to use paths relative to your project directory before uploading it. Ensure that the required CSV files are available in the expected locations.

## 📚 Project Scope

This project focuses on **data cleaning, exploratory data analysis, statistical summaries, and data visualization**.

It does not implement machine learning models or predictive analysis.

## 🔮 Future Improvements

Potential improvements include:

* Improving the presentation and interpretation of visualizations.
* Adding interactive dashboard functionality.
* Performing more detailed statistical analysis.
* Investigating relationships between socioeconomic and digital-access variables.
* Improving data validation and documenting the survey's source and sampling methodology.

## 👨‍💻 Author

Developed as a Python-based data science project exploring Nepal household survey data.

## 📄 License

Add a suitable license if you intend to distribute this project publicly. Ensure that the dataset's terms and any privacy requirements permit redistribution before uploading the raw or cleaned survey data.
