FBI NIBRS Data Analysis: Risk Trends & Intervention Strategies (2021-2023)
Executive Summary
This project utilizes Python-based data automation to analyze over 50,000+ records from the FBI's Uniform Crime Reporting (UCR) Program. The objective was to model state-level risk trends and identify high-variance anomalies in hate crime reporting.

By aggregating and cleaning raw disparate datasets, this analysis provides a data-driven foundation for strategic resource allocation and targeted intervention policies.

Key Insights & Risk Indicators
Trend Identification: Modeled year-over-year volatility in hate crime incidents to forecast potential high-risk regions.

Geographic Distribution: Identified specific states with disproportionate incident rates, enabling focused "audit" of local prevention resources.

Offender Profiling: analyzed offender demographics to inform community-based support initiatives.

Visualizations
<img width="916" height="504" alt="image" src="https://github.com/user-attachments/assets/f46df53c-fd86-4166-8dbd-9499737c39ba" />
<img width="927" height="944" alt="image" src="https://github.com/user-attachments/assets/b6db30bc-821c-473b-bc51-3e0752f42060" />
<img width="747" height="629" alt="image" src="https://github.com/user-attachments/assets/66c1f1f6-2944-48a7-965a-bdc005d82696" />



Technical Methodology (ETL & Data Integrity)
To ensure accurate reporting for stakeholders, a rigorous Extract, Transform, Load (ETL) process was applied:

Data Ingestion: Merged multiple annual FBI Hate Crime Statistics reports into a unified dataset (by_state_hate_crimes.csv).

Data Cleaning & Validation:

Standardized inconsistent state/category labels.

Outlier Detection: Applied statistical methods to identify and segregate anomalous data points that could skew risk modeling.

Null Value Handling: Implemented logic to address missing fields without compromising dataset integrity.

Visualization: Leveraged Seaborn and Matplotlib to translate raw figures into executive-level dashboards.

Tools & Technologies
Language: Python 3.x

Data Manipulation: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Version Control: Git

Business Value
This analysis serves three key stakeholder groups:

Law Enforcement (Operations): Optimizes resource allocation to high-incident "hotspots."

Policy Makers (Governance): providing evidence-based metrics to validate the effectiveness of current prevention strategies.

Community Organizations (Risk Mitigation): Enables proactive rather than reactive support systems.

Usage
The complete analysis, including code for data cleaning and visualization, is documented in the Jupyter Notebook:

jupyter notebook finalZR.ipynb

Or you can simply click on the file in this github repository titled, "finalZR.ipynb"
