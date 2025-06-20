# Megaline Customer Analysis

## Overview
This project delivers a comprehensive analysis of Megaline's telecom customer data to uncover usage patterns, customer segments, and actionable insights for business growth. The notebook guides you through data exploration, preprocessing, modeling, and interpretation to support data-driven decision-making for Megaline.

## Features
- **Data Exploration:** Detailed examination of call, internet, message, plan, and user data.
- **Data preparation:** Meticulous cleaning,feature engineering and integration of datasets into a comprehensive general dataset.
- **Visualization:** Clear charts and graphs to highlight trends and findings.
- **User Behaviour Analysis and service consuption:** Identification of key customer groups and their behaviors. Clear analysis of service consumption (Geographically, by user, by day...)
- **Hypothesis testing:** We will conduct a hypothesis testing to compare different populations. In this case we will conduct a comparison between the total revenue coming from the two different available plans.
- **Business Insights:** Recommendations for customer retention, plan optimization, and revenue growth.

## How to Use
1. Clone this repository or download the notebook.
2. Ensure you have the required dependencies (see below).
3. Open `megaline_analysis.ipynb` in Jupyter Notebook or VS Code.
4. Run the cells sequentially to reproduce the analysis and results.

## Requirements
- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn

Install dependencies with:
```bash
pip install -r requirements.txt
```

## Data
The analysis uses Megaline's anonymized datasets, including:
- `megaline_calls.csv`
- `megaline_internet.csv`
- `megaline_messages.csv`
- `megaline_plans.csv`
- `megaline_users.csv`

All data files are located in the `data/` directory.

## Project Structure
```
megaline/
├── megaline_analysis.ipynb
├── data/
│   ├── megaline_calls.csv
│   ├── megaline_internet.csv
│   ├── megaline_messages.csv
│   ├── megaline_plans.csv
│   └── megaline_users.csv
└── README.md
```

## Results
- Discovered key usage trends and customer segments.
- Provided actionable recommendations for Megaline's business strategy.

## License
This project is for educational and demonstration purposes.