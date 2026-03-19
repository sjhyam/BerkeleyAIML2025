# Capstone Project: Housing Affordability Stress in High-Growth U.S. Metros

**Author**: Shyamsunder Mutcha  
**Program**: UC Berkeley Professional Certificate in Machine Learning and Artificial Intelligence

### Executive Summary
This capstone explores how macroeconomic conditions (unemployment, inflation) and job-market factors influence housing affordability in U.S. metros, with a focus on Apex, NC (Raleigh-Cary MSA). Early EDA (Modules 1–6) uses descriptive statistics, distributions, and visualizations on public BLS and Census data.

### Rationale
Housing affordability affects millions — especially in tech-driven growth areas where jobs are plentiful but home prices outpace incomes. Understanding these pressures helps individuals make better rent/buy/relocate decisions.

### Research Question
To what extent do current macroeconomic conditions (inflation via CPI and local unemployment rates) and job-market indicators (wage levels in technology occupations) influence housing affordability stress (measured by rent burden and home price-to-income ratio) in U.S. metropolitan areas, with a focus on Apex, NC (Raleigh-Cary MSA)?

### Data Sources
- BLS: Unemployment rates and OEWS wages (Raleigh-Cary MSA) — https://www.bls.gov/data/
- Census ACS 5-year: Median home value (B25077), rent burden (B25074), household income — https://api.census.gov/data/2023/acs/acs5
- FRED: CPI inflation — https://fred.stlouisfed.org

### Methodology
- Data ingestion & cleaning (pandas, requests)
- Descriptive statistics & distribution analysis (scipy.stats)
- Visualizations (seaborn/matplotlib): histograms, scatter, boxplots, heatmaps
- Basic correlation analysis

### Results
- Raleigh-Cary MSA (Apex ZIP 27502) shows low unemployment (~3.2%) but high median home values (~$565,000), yielding a ~4.0x price-to-income ratio.
- Home values are right-skewed (typical of growth metros).
- Lower unemployment correlates with higher prices → income growth doesn't fully offset housing pressure.
- Rent burden moderate (~28.5%) but vulnerable to inflation.
- Visuals: [See notebook plots: distribution, scatter, boxplot, heatmap]

### Next Steps
- Expand dataset to 10+ metros for clustering (Mod 6).
- Add linear regression (Mod 7) to quantify relationships.
- Incorporate time-series CPI trends (Mod 10) and classification (Mod 12) for stress prediction.
- Develop GenAI summaries (later modules).

### Outline of Project
- [capstone_eda.ipynb](capstone_eda.ipynb) – Capstone EDA

### Contact
sjhyam@gmail.com / https://www.linkedin.com/in/shyamsunder-mutcha-5883881/
