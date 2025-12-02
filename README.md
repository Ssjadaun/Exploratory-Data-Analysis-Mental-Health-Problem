# Exploratory Data Analysis: Mental Health Problems

## About

This repository provides comprehensive exploratory data analysis (EDA) focusing on mental health problems. Through data-driven insights, we aim to understand and address key challenges in mental health, helping individuals and organizations make informed decisions about mental well-being.

## Overview

Mental health is a critical aspect of overall well-being that affects millions of people worldwide. This project analyzes various factors that influence mental health, including:

- **Demographic factors**: Age, gender, education, marital status
- **Lifestyle factors**: Sleep patterns, physical activity levels
- **Work-related factors**: Working hours, stress levels, work-life balance
- **Social factors**: Social support networks, treatment-seeking behavior

## Project Structure

```
├── data/
│   └── mental_health_survey.csv     # Survey dataset
├── notebooks/
│   └── mental_health_eda.ipynb      # Main EDA notebook
├── requirements.txt                  # Python dependencies
├── LICENSE                           # MIT License
└── README.md                         # This file
```

## Dataset

The dataset contains 100 survey responses with the following features:

| Feature | Description |
|---------|-------------|
| `age` | Age of the respondent |
| `gender` | Gender identity (Male/Female/Non-binary) |
| `occupation` | Current occupation |
| `work_hours_per_week` | Average working hours per week |
| `sleep_hours_per_day` | Average sleep hours per day |
| `physical_activity_days_per_week` | Days of physical activity per week |
| `stress_level` | Self-reported stress level (Low/Medium/High) |
| `anxiety_score` | Anxiety assessment score (1-10) |
| `depression_score` | Depression assessment score (1-10) |
| `has_sought_treatment` | Whether treatment has been sought (Yes/No) |
| `work_life_balance` | Self-reported work-life balance rating |
| `social_support` | Level of social support (Poor/Fair/Good/Excellent) |
| `income_level` | Income bracket (Low/Medium/High) |
| `education_level` | Highest education achieved |
| `marital_status` | Marital status |
| `has_chronic_condition` | Presence of chronic health conditions |
| `overall_mental_health_score` | Composite mental health score (1-100) |

## Key Insights

### 1. Lifestyle Impact
- **Sleep**: Strong positive correlation between adequate sleep (7-8 hours) and better mental health scores
- **Physical Activity**: Regular exercise (4-5 days/week) is associated with lower anxiety and depression scores

### 2. Work Factors
- High stress levels significantly impact mental health (20+ point difference in scores)
- Poor work-life balance correlates with higher anxiety and depression

### 3. Social Support
- Excellent social support leads to 15-20 point higher mental health scores compared to poor support
- Strong support networks are protective against mental health challenges

### 4. High-Risk Groups
- Workers in high-pressure occupations (executives, investment bankers)
- Individuals with excessive working hours (>55 hours/week)
- Those with limited social support networks

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Ssjadaun/Exploratory-Data-Analysis-Mental-Health-Problem.git
cd Exploratory-Data-Analysis-Mental-Health-Problem
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook notebooks/mental_health_eda.ipynb
```

## Requirements

- Python 3.8+
- pandas >= 1.3.0
- numpy >= 1.21.0
- matplotlib >= 3.4.0
- seaborn >= 0.11.0
- jupyter >= 1.0.0
- scikit-learn >= 0.24.0

## Analysis Sections

1. **Data Loading and Exploration**: Understanding the dataset structure and quality
2. **Data Cleaning**: Handling missing values and data preprocessing
3. **Demographic Analysis**: Distribution of respondents by demographics
4. **Mental Health Indicators**: Analysis of anxiety, depression, and overall scores
5. **Lifestyle Factors**: Impact of sleep and physical activity
6. **Work-Related Analysis**: Effects of work hours, stress, and work-life balance
7. **Social Support Analysis**: Importance of social connections
8. **Correlation Analysis**: Relationships between different factors
9. **Occupation-Based Insights**: Mental health by profession
10. **Age Group Analysis**: Mental health patterns across age groups
11. **Key Findings and Recommendations**: Actionable insights

## Recommendations

### For Individuals
- Prioritize 7-8 hours of quality sleep
- Engage in regular physical activity
- Build and maintain strong social support networks
- Seek professional help when needed

### For Organizations
- Implement work-life balance programs
- Provide mental health resources and support
- Offer stress management training
- Create a supportive workplace culture

### For Policy Makers
- Invest in mental health awareness campaigns
- Ensure accessible and affordable mental health services
- Establish reasonable workplace regulations

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project aims to contribute to the understanding of mental health challenges and promote data-driven approaches to mental well-being.
