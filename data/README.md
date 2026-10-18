### Data

This folder contains the cleaned NYC Airbnb dataset used for the analysis and Power BI dashboard.

### Dataset Overview

* **Source:** NYC Airbnb Open Data (2019)

* **Records:** 48,895 listings

* **Columns:** 16

* **Tools:** Python and Pandas

### Data Preparation

The dataset was cleaned and validated before analysis. Missing values were handled appropriately, duplicate records were checked, and 11 listings with zero nightly prices were excluded from price calculations by replacing those values with missing values.

A separate CSV export was prepared for Power BI by removing line breaks from text fields to ensure proper data import.

### File

* **nyc_airbnb_powerbi.csv** — cleaned dataset prepared for Power BI analysis.

### Important Note

This dataset represents Airbnb listings in New York City in 2019. Nightly listing prices do not represent actual revenue or profitability.
