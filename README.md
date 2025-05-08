# Housing Data: Historical State-Level Housing Price Estimation

This repository documents a data wrangling process to estimate historical housing prices for U.S. states from FHFA House Price Index (HPI) values using 1980 Census-based median home prices as a baseline.

---

## Repository Contents

- `corrected_state_base_prices_1980.csv`:  
  A manually cleaned CSV of median home prices by state in 1980, extracted from U.S. Census data.
  
- `hpi_at_state.csv`:  
  FHFA’s All-Transactions House Price Index (HPI) data, reported quarterly by state using index values (base year: 1980 = 100).

- `housing_prices_for_tobe.csv`:  
  Output file containing estimated average home prices per year per state by scaling the HPI index using 1980 baseline prices.

- `Housing_data_for_tobe.qmd`:  
  A Quarto script documenting the data cleaning, joining, and calculation process.

---


## Tools Used

- R with `dplyr` for data manipulation
- Quarto for documentation and reproducibility
- GitHub for version control


---

## Author

Created by [@nickli1209](https://github.com/nickli1209)  
Data from FHFA & U.S. Census Bureau.
