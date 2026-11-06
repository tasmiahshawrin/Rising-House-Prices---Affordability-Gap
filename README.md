Overview:
Analyses UK housing affordability (2020-2024) using Land Registry house prices and ONS income (GDHI per head). Affordability ratio = median house price ÷ GDHI per head. It answers 5 questions: price vs income growth, regional gaps, income-price correlation, property type differences, and the pandemic boom vs rate-rise period.

Dataset Source:
   1. gross-disposable-household-income-per-head.csv: 
   https://www.ons.gov.uk/explore-local-statistics/indicators/gross-disposable-household-income-per-head#get-the-data
   3. pp-2020.csv, pp-2021.csv, pp-2022.csv, pp-2023.csv, pp-2024.csv:
   https://www.gov.uk/government/statistical-data-sets/price-paid-data-yearly-file

Execution Instructions: 
   1. Open housing_affordability.ipynb using Jupyter Notebook
   2. Install the required libraries: pandas, numpy, and matplotlib
   3. Update CSV file paths
   4. Run all cells sequentially 

Dependencies: pandas, numpy, matplotlib, jupyter.

File Descriptions:
   1. Source Code: housing_affordability.ipynb
   2. Raw Datasets: gross-disposable-household-income-per-head.csv, pp-2020.csv, pp-2021.csv, pp-2022.csv, pp-2023.csv, pp-2024.csv
   3. Cleaned Datasets: cleaned_house_price_dataset.csv, cleaned_income_dataset.csv, la_annual_affordability.csv, property_type_affordability.csv, regional_affordability.csv
   4. Merged Datasets: merged_house_price_dataset.csv, merged_housing_affordability.csv

Member Contribution:
   1. Tasmiah Haque (24-59834-3): Data collection, merging of the house price datasets, data analysis and cleaning, RQ1, RQ2 
   2. Taibun Sayed (24-58839-2): Data collection, income dataset analysis and cleaning, geographical harmonisation, RQ3
   3. Ovi Ghosh (25-61733-1): EDA and Summary statistics, RQ5
   4. MD.Hasnat (25-61087-1): RQ4, report writing
   5. MD Shazzadul Islam (24-58756-2): No contribution
