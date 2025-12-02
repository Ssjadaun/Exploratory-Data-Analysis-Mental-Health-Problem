# Exploratory Data Analysis — Mental Health in Tech

A concise, reproducible exploratory data analysis (EDA) project examining mental health in the technology industry. This repository contains notebooks, visualizations, and helper scripts that analyze the OSMI "Mental Health in Tech" survey to surface patterns, correlations, and actionable insights.

Dataset
- OSMI: Mental Health in Tech Survey (Kaggle)
  - https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey

Table of contents
- Project overview
- Goals & research questions
- Data source & contents
- Methods & tools
- Key findings (summary)
- How to reproduce / run notebooks
- Repository structure
- Contributing
- License
- Acknowledgements & references
- Contact

Project overview
This mini-project performs EDA on a survey about mental health in the technology workplace. It aims to describe respondent demographics, evaluate prevalence and treatment-seeking behavior, and explore relationships between workplace culture (e.g., employer support, benefits) and mental health outcomes.

Analyses include:
- Descriptive statistics (age, gender, role, country)
- Prevalence of self-reported mental health conditions and treatment
- Association of workplace support and benefits with care-seeking
- Visualizations to surface trends and disparities by demographic groups

Goals & research questions
Primary goals:
- Describe the survey population and key mental-health measures
- Identify factors associated with seeking treatment
- Explore how workplace environment relates to mental health outcomes
- Produce reproducible visualizations and a concise set of insights

Example research questions:
- What share of respondents report a mental health condition?
- How many have access to employer-provided mental health benefits?
- Do specific demographic groups report different treatment-seeking behaviors?
- Is workplace support associated with higher likelihood of seeking care?

Data source
This analysis uses the Kaggle copy of the OSMI "Mental Health in Tech Survey":
https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey

The repository contains notebooks that expect you to supply the original dataset locally. Please review the dataset license and Kaggle terms before redistributing raw data.

Methods & tools
Primary tools:
- Python 3.x
- pandas — data cleaning and manipulation
- matplotlib / seaborn / plotly — visualizations
- Jupyter Notebook / JupyterLab — exploratory narrative
- scikit-learn (optional) — simple modeling or encoding

Typical workflow:
1. Load and inspect the CSV(s)
2. Clean and normalize fields (e.g., standardize country names, handle missing values)
3. Create derived variables (e.g., indicators for treatment and benefits)
4. Run descriptive analyses and group-bys
5. Visualize distributions and relationships
6. Summarize findings and recommendations

Key findings (example)
Replace this section with final results from your notebooks. Example:
- X% of respondents report experiencing a mental health condition; Y% sought treatment.
- Respondents who report a supportive workplace are N% more likely to seek treatment.
- Access to employer-provided benefits varies by country and company size.
- Stigma and fear of workplace consequences remain frequent barriers.

How to run / reproduce
1. Clone the repo:
   git clone https://github.com/Ssjadaun/Exploratory-Data-Analysis-Mental-Health-Problem.git
2. Create and activate a virtual environment:
   python -m venv .venv
   source .venv/bin/activate  # macOS / Linux
   .\.venv\Scripts\activate   # Windows
3. Install dependencies:
   pip install -r requirements.txt
   (If requirements.txt is not present, install pandas, matplotlib, seaborn, plotly, jupyterlab.)
4. Place original Kaggle CSV(s) in data/ or update notebook paths.
5. Start Jupyter:
   jupyter lab
   or
   jupyter notebook
6. Run notebooks end-to-end; notebooks will note any intermediate files created in data/ or outputs/.

Repository structure (example)
- notebooks/          — Jupyter notebooks with the EDA
- data/               — (not checked in) raw and processed datasets
- src/                — helper scripts for cleaning and plotting (optional)
- outputs/            — generated figures and summary tables
- README.md           — this file
- requirements.txt    — Python dependencies

Contributing
Contributions are welcome. Suggestions:
- Improve data cleaning and reproducibility
- Add more visualizations or an interactive dashboard
- Add written interpretations for each figure
- Open an issue or submit a PR with proposed changes

License
Specify a license (e.g., MIT) and add a LICENSE file. If none is specified, add one before reusing code.

Acknowledgements & references
- OSMI Mental Health in Tech Survey (Kaggle): https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey
- OSMI — Open Sourcing Mental Illness

Contact
Author: Ssjadaun  
If you want, I can prepare a pull request with this update — tell me if you'd like that and whether you'd like any further edits (badges, screenshots, or shorter summary).
