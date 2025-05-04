# South Africa Load Shedding Analysis

This project analyzes historical load shedding data in South Africa. The goal is to uncover trends, distributions, and temporal patterns of load shedding stages using Python and data visualization tools.

## Dataset

- **File:** `south_africa_load_shedding_history.csv`
- **Source:** The dataset contains timestamps (`created_at`) and load shedding stages over time.

## Project Structure
project/
│
├── data/
│   └── south_africa_load_shedding_history.csv
│
├── visuals/
│   └── (generated charts will be saved here if implemented)
│
├── notebooks/
│   └── load_shedding_analysis.ipynb
│
├── src/
│   └── (optional: Python scripts used for preprocessing or analysis)
│
├── .gitignore
├── requirements.txt
└── README.md

## Features

- Loads and preprocesses load shedding data.
- Extracts datetime features like year, month, hour.
- Performs descriptive statistics.
- Visualizes:
  - Load shedding stage trends over time.
  - Average stage per month.
  - Distribution of stages.
  - Hourly patterns.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/MellonP/load-shedding-analysis.git

   Here's a complete README.md for your load shedding data analysis project:


---

# South Africa Load Shedding Analysis

This project analyzes load shedding trends in South Africa using historical stage data. It includes data cleaning, exploration, and visualizations to uncover patterns over time and across different time periods.

## Dataset

- **File**: `south_africa_load_shedding_history.csv`
- **Source**: [Your source or link if applicable]
- **Contents**: Timestamped records of load shedding stages in South Africa.

## Project Structure

. ├── data/ │   └── south_africa_load_shedding_history.csv ├── notebooks/ │   └── load_shedding_analysis.ipynb ├── visuals/ │   └── (Generated plots/images) ├── .gitignore ├── README.md └── requirements.txt

## Features

- Loads and preprocesses load shedding data.
- Extracts datetime features like year, month, hour.
- Performs descriptive statistics.
- Visualizes:
  - Load shedding stage trends over time.
  - Average stage per month.
  - Distribution of stages.
  - Hourly patterns.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/load-shedding-analysis.git
   cd 

## Install dependencies:

pip install -r requirements.txt
Launch Jupyter Notebook:

## Requirements
Python 3.x
pandas
matplotlib
seaborn
numpy
jupyter 


## License

This project is open-source and available under the MIT License.
