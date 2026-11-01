# 🏏 IPLytics — IPL Data Analysis & Insights

An end-to-end exploratory data analysis project on the Indian Premier League (IPL), using Python to uncover insights into team performances, player statistics, match outcomes, and venue trends.

## 📌 Project Overview

**IPLytics** is a data analysis project that explores IPL match and ball-by-ball delivery data to identify meaningful cricket insights.

The project uses Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn for data cleaning, analysis, statistical exploration, and visualization.

## 🎯 Project Objectives

- Explore and understand IPL match and delivery datasets.
- Clean and preprocess raw cricket data.
- Analyze team performance across IPL seasons.
- Evaluate batting and bowling performances.
- Study the impact of toss decisions on match outcomes.
- Compare player statistics and identify top performers.
- Analyze scoring patterns and venue-wise trends.
- Present findings through meaningful visualizations.

## 📂 Datasets

The project uses two datasets:

| Dataset | Description | Records |
|---|---|---:|
| `matches.csv` | Match-level information, including teams, venues, toss decisions, and results | 1,095 |
| `deliveries.csv` | Ball-by-ball information, including batsmen, bowlers, runs, and wickets | 260,920 |

The original datasets are stored in `data/raw/`, while cleaned datasets are stored in `data/processed/`.

## 🛠️ Technologies Used

- **Python 3.12** — Programming language
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical computations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Jupyter Notebook** — Interactive analysis

## 📊 Project Analysis

The project is organized into four stages:

### 1. Data Exploration
- Dataset dimensions, columns, and data types.
- Statistical summaries.
- Missing-value analysis.
- Duplicate and data consistency checks.
- Initial exploration of IPL seasons and match outcomes.

### 2. Data Cleaning
- Handling missing city values using venue information.
- Converting date columns into datetime format.
- Validating run calculations and wicket indicators.
- Checking match ID consistency.
- Saving cleaned datasets for further analysis.

### 3. Exploratory Data Analysis (EDA)
- Team-wise match and win analysis.
- Team win percentages.
- Toss decisions and their relationship with match outcomes.
- Season-wise match trends.
- Match-result distribution.

### 4. Advanced Analysis & Cricket Insights
- Top batsmen and batting strike rates.
- Bowling economy rates and wicket-taking performances.
- Player comparisons and all-rounder analysis.
- Team scoring patterns.
- Venue-wise match and scoring analysis.

## 🔍 Key Insights

Some findings from the analysis include:

- **Virat Kohli** recorded 8,014 runs in the analyzed dataset.
- **Yuzvendra Chahal** recorded 205 wickets.
- **Sunil Narine** recorded a bowling economy rate of 6.74 in the analysis.
- **Ravindra Jadeja** contributed 2,959 runs and 160 wickets.
- **Mumbai Indians** recorded 42,133 cumulative runs.
- **Gujarat Titans** had an average score of 172.38 in the analyzed data.
- **Wankhede Stadium** hosted 118 matches.
- **Chennai Super Kings** recorded a win percentage of 57.98% in the team analysis.

*These findings are based on the datasets and analysis performed in this project.*

## 📁 Project Structure

```text
ipl-data-analysis/
│
├── data/
│   ├── raw/
│   │   ├── matches.csv
│   │   └── deliveries.csv
│   │
│   └── processed/
│       ├── matches_cleaned.csv
│       └── deliveries_cleaned.csv
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_eda.ipynb
│   └── 04_advanced_analysis.ipynb
│
├── src/
├── tests/
├── visualizations/
│
├── main.py
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/ARYANROY20/ipl-data-analysis.git
cd ipl-data-analysis
```

### 2. Create a Conda environment

```bash
conda create --prefix ./venv python=3.12
```

### 3. Activate the environment

```bash
conda activate ./venv
```

### 4. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 5. Open the project in VS Code

```bash
code .
```

Open the `notebooks/` folder and select the appropriate Python 3.12 kernel for executing the notebooks.

Execute the notebooks in this order:

1. `01_data_exploration.ipynb`
2. `02_data_cleaning.ipynb`
3. `03_eda.ipynb`
4. `04_advanced_analysis.ipynb`

### Dataset Availability

The original datasets in `data/raw/` are excluded from Git tracking.

To reproduce the complete workflow, place the original `matches.csv` and `deliveries.csv` files inside `data/raw/` before running the notebooks.

The cleaned datasets are maintained in `data/processed/`.

## 🚀 Future Improvements

- Extend the analysis with additional IPL performance metrics.
- Explore more advanced statistical relationships.
- Improve the range and presentation of visualizations.
- Investigate additional player and team performance trends.

