# GameInsightsML

## Overview

GameInsightsML is a machine learning project designed to unravel patterns in video game sales and ratings. By exploring industry trends, genre preferences, and the interplay of critic and user reviews, the project sheds light on the factors influencing game success.

## Dataset

The dataset, generously shared by [Sumit Kumar Shukla](https://www.kaggle.com/thedevastator), is accessible on Kaggle: [Video Game Sales and Ratings Dataset](https://www.kaggle.com/datasets/thedevastator/video-game-sales-and-ratings).

## Phases

1. **Initiation:**
   - Defined project objectives and acquired the dataset.
   - Established the project structure.

2. **Preprocessing:**
   - Addressed missing values, cleaned, and transformed the data.
   - Conducted feature engineering and categorical variable encoding.
   - Scaled numeric features for uniform analysis.

3. **EDA:**
   - Utilized descriptive statistics and visualized correlations.
   - Explored genre and platform preferences, revealing industry trends.
   - Analyzed the relationship between critic and user scores.
   - Uncovered key numerical feature observations.

4. **Model Development:**
   - Employed the Random Forest Regressor model.
   - Achieved a Mean Squared Error (MSE) of 0.70 and an impressive R-squared of 0.83.

5. **Predictive Analysis:**
   - Explored strategies for business decision support and market segmentation based on predictive modeling.

6. **Impact Assessment:**
   - Investigated how critic reviews impact user reviews.
   - Conducted a comparative study between different gaming platforms, uncovering nuances in commercial success.

7. **Documentation:**
   - Compiled a concise README summarizing the project phases and key findings.

## Key Findings

### 1. Global and Regional Sales Correlation:
- **Observation:** Strong positive correlations were identified between global sales and sales figures in North America and Europe.
- **Implication:** Games that perform well in specific regions tend to achieve high global sales, emphasizing the importance of regional preferences in marketing strategies.

### 2. Critic and User Scores Dynamics:
- **Observation:** A positive but moderate correlation (~0.35) exists between critic and user scores.
- **Implication:** While there is alignment in the perception of game quality between critics and users, variations suggest differing evaluation criteria.

### 3. Critic Scores and Sales:
- **Observation:** Positive correlations exist between critic scores and both global and regional sales.
- **Implication:** Higher critic scores are associated with higher sales, indicating the impact of critical acclaim on commercial success.

### 4. User Scores and Sales:
- **Observation:** A positive but relatively weak correlation exists between user scores and sales figures.
- **Implication:** User scores have a milder influence on sales compared to critic scores, suggesting other factors play a significant role in shaping user preferences.

### 5. Critic and User Counts Influence:
- **Observation:** The number of critics and users who reviewed a game are positively correlated.
- **Implication:** Popular games attract more reviews from both critics and users, acting as indicators of a game's popularity and visibility in the market.

## Model

Random Forest Regressor:
- MSE: 0.70
- R-squared: 0.83

## Author

Suleyman Yahaya

## Usage

1. Clone the repository.
2. Execute `GameInsightsML.ipynb`.

## Dependencies

- pandas
- scikit-learn
- matplotlib
- seaborn

## Acknowledgments

Dataset provided by [Sumit Kumar Shukla](https://www.kaggle.com/thedevastator).

## Conclusion

GameInsightsML uncovers valuable insights into video game industry trends, leveraging machine learning to illuminate critical factors influencing game success.
