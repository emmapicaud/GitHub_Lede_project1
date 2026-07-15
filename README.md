# eu-carbon-market-investigation

## 📊 Project at a glance

- 🏭 **10,000+ industrial installations**
- 🌍 **27 European countries**
- 📅 **21 years of data (2005–2025)**
- 🗂 **Multiple public and market datasets**
- 🐍 **Python + Pandas workflow**
- 📈 **20+ analytical tables generated**

## 📚 Sources & Methodology

<table>
<tr>
<td>

### Data sources

This analysis is primarily based on official European datasets, with a particular focus on the **European Union Emissions Trading System (EU ETS) Registry**, published by the **European Environment Agency (EEA)**.

The registry contains information for **more than 10,000 industrial installations** covered by the EU carbon market from **2005 to 2025**, including:

- CO₂ allowance allocations
- Verified emissions
- Installation identifiers
- Economic sectors
- Country-level information

Additional public datasets were used to validate and enrich the analysis, including data from:

- 🇪🇺 European Environment Agency (EEA)
- 🇪🇺 European Commission
- 📈 European Energy Exchange (EEX), one of Europe's main carbon allowance trading platforms

</td>
</tr>
</table>

---

## 🔬 Methodology

<table>
<tr>
<td>

The project combines official administrative datasets with market data to reconstruct the evolution of the EU ETS over the last twenty years.

The workflow included:

- Cleaning and harmonizing multiple datasets
- Matching installations across different data sources
- Standardizing country and sector classifications
- Aggregating emissions and allowance allocations by year, sector and country
- Comparing emissions with allocated and auctioned allowances
- Integrating historical carbon price data from the EEX

The final dataset covers the entire lifetime of the EU ETS, from its launch in **2005** through **2025**, allowing long-term analysis of emissions, free allocations and carbon pricing.

</td>
</tr>
</table>

---

<p align="center">

| Dataset | Source | Coverage |
|:--------|:------|:---------|
| EU ETS Registry | European Environment Agency | 2005–2025 |
| Verified emissions | European Environment Agency | 2005–2025 |
| Allowance allocations | European Environment Agency | 2005–2025 |
| Carbon prices (EUA) | European Energy Exchange (EEX) | Historical market prices |
| Regulatory documentation | European Commission | EU ETS legislation |


## 🛠 Technical Overview

| | |
|---|---|
| **Programming language** | Python 3 |
| **Main libraries** | Pandas, NumPy, Matplotlib, Jupyter Notebook |
| **Data sources** | European Environment Agency (EEA), European Commission, European Energy Exchange (EEX) |
| **Time coverage** | 2005–2025 |
| **Geographical scope** | 27 EU Member States |
| **Industrial installations** | 10,000+ |
| **Years analysed** | 21 |
| **Output datasets** | 20+ cleaned and aggregated tables |

## ⚙️ Data Engineering Challenges

This project required much more than downloading a single dataset. The analysis involved cleaning, restructuring and combining multiple administrative and market datasets covering more than twenty years of EU carbon market activity.

### Main challenges

- Merging multiple datasets published in different formats and update cycles.
- Harmonizing installation identifiers across years.
- Cleaning inconsistent sector and country classifications.
- Separating allowance allocations from verified emissions contained in the same registry tables.
- Handling missing values, duplicated records and historical changes in reporting.
- Building reproducible aggregation pipelines for countries, sectors and installations.
- Integrating historical EUA carbon prices from the European Energy Exchange (EEX).
- Producing standardized datasets suitable for visualization and statistical analysis.

## 💻 Technical Skills Demonstrated

### Data processing

- Pandas
- NumPy
- Jupyter Notebook

### Data wrangling

- Data cleaning
- Merge and join operations
- Pivot tables
- GroupBy aggregations
- Reshaping datasets
- Missing-value handling
- Deduplication
- Data validation

### Analysis

- Exploratory Data Analysis (EDA)
- Time-series analysis
- Sectoral comparison
- Country-level aggregation
- Carbon market analysis

### Reproducibility

- Modular notebooks
- Version-controlled datasets
- Documented methodology
</p>