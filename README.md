## Instructor Effectiveness Analysis (EdTech)

## Project Overview
This project evaluates instructor performance on an EdTech platform using learner engagement and outcome metrics. The goal is to classify instructors into effectiveness tiers and identify key factors influencing teaching impact. Insights from this analysis can guide instructor assessment, optimize course delivery, and enhance learner outcomes.

## Key Features
- Analysis of learner metrics including:
  - Completion Rate
  - Dropout Rate
  - Average Score Improvement
  - Average Quiz Score
  - Watch Time & Assignment Submissions
- Identification of strongest indicators of instructor effectiveness.
- Classification of instructors into **Low**, **Medium**, and **High** effectiveness tiers using a **Random Forest** model.
- Visualizations for insights on performance patterns and feature importance.

## Tools & Libraries
- **Python**
- **pandas** – Data manipulation
- **numpy** – Numerical computations
- **scikit-learn** – Machine learning modeling
- **matplotlib / seaborn** – Data visualization

## Insights
- Key predictors of instructor effectiveness include effectiveness score, average score improvement, dropout rate, and completion rate.
- Random Forest modeling provides high predictive accuracy for tier classification.
- Recommendations for real-world application include combining quantitative analysis with qualitative feedback and contextual data for comprehensive evaluations.

## How to Run
1. Clone the repository.
2. Ensure the required Python libraries are installed:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
