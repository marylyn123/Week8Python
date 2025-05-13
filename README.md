README.md
COVID-19 Global Data Tracker
This repository contains a Jupyter Notebook that analyzes global COVID-19 data. The notebook performs data loading, cleaning, exploratory analysis, and visualization of COVID-19 cases, deaths, and vaccinations for selected countries.
Description
The COVID-19 Global Data Tracker project demonstrates key steps in analyzing pandemic data. We use a provided CSV dataset (or OWID data) to:
Load and preview global COVID-19 statistics.
Clean and filter the data for specific countries (e.g., USA, India, Kenya).
Visualize key metrics like total cases, total deaths, and case fatality rates.
(Demonstration) Compare vaccination coverage across countries.
Highlight important trends and disparities in the data.
The notebook is designed to be beginner-friendly, with clear code comments and explanations.
Objectives
Data Loading: Import COVID-19 data and understand its structure.
Data Cleaning: Handle missing values and filter data for analysis.
Exploratory Analysis: Create charts of case counts, deaths, and death rates.
Vaccination Analysis: Plot vaccination rates across countries (illustrative).
Insights: Summarize findings on trends and global disparities.
Tools Used
Python 3
Pandas (data manipulation)
Matplotlib and Seaborn (data visualization)
Plotly (for optional interactive map)
Jupyter Notebook (analysis environment)
How to Run
Clone the repository or download the notebook and the covid_data.csv file.
Ensure you have the required Python libraries installed. You can install them via:
nginx
Copy
Edit
pip install pandas matplotlib seaborn plotly
Open the notebook (COVID-19_Global_Data_Tracker.ipynb) in JupyterLab or Jupyter Notebook.
Run each cell sequentially to reproduce the analysis and plots.
The outputs (plots and tables) will appear inline in the notebook.
Summary of Findings
The United States and India have the largest COVID-19 case counts by far, driven by their large populations. As of the data, the US had ~111.8M cases and 1.22M deaths, while India had ~45.0M cases and 0.53M deaths
worldometers.info
.
Case fatality rates are over 1% in both countries (≈1.1% USA, ≈1.2% India). Some smaller countries (e.g. Kenya) show higher CFRs, which may reflect demographic or reporting differences.
Vaccination coverage is much higher in rich countries. About 67% of people in the US and India are fully vaccinated
en.wikipedia.org
ycharts.com
, compared to roughly 28% in low-income countries
data.one.org
. This highlights a large gap in vaccine distribution.
The data analysis emphasizes global inequity: wealthier nations achieved higher testing and vaccination rates, while poorer countries lag behind. Addressing these disparities is crucial for controlling the pandemic worldwide.
