# Aviation Wildlife Strike — Data Analysis

An end-to-end data analysis project investigating wildlife strike incidents in US aviation. Working from a business brief, the analysis explores strike frequency, animal types, conditions, and which airlines and airports are most affected — producing data-driven recommendations for a fictional safety equipment company.

## Tech Stack

- **Language:** Python
- **Libraries:** pandas, redshift_connector
- **Environment:** Jupyter Notebook
- **Data warehouse:** AWS Redshift

## Project Structure

```
aviation-wildlife-strike-data-analysis/
├── wildlife-strike-analysis.ipynb   # Full analysis notebook
├── requirements.txt
└── README.md
```

## Analysis Questions

The notebook investigates:

1. How significant a problem are wildlife strikes overall?
2. Are strikes by particular animals more dangerous than others?
3. When and under what conditions are strikes most likely?
4. Which airlines, airports, and states are the most likely customers for safety products?

All findings are backed by the data and the process is fully documented and auditable within the notebook.

## Setup

```bash
git clone https://github.com/Webbie-AAA/aviation-wildlife-strike-data-analysis
cd aviation-wildlife-strike-data-analysis
pip install -r requirements.txt
```

Set your Redshift connection credentials as environment variables:

```
REDSHIFT_HOST=<your-redshift-endpoint>
REDSHIFT_DB=<your-db-name>
REDSHIFT_USER=<your-user>
REDSHIFT_PASSWORD=<your-password>
```

Then open the notebook:

```bash
jupyter notebook wildlife-strike-analysis.ipynb
```

## Context

Assessment project completed as part of the Sigma Labs Data Engineering Training Programme (Dec 2025 – Feb 2026). Included a presentation of findings and recommendations to a non-technical audience.
