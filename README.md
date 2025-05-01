# NBA Player Stats Analysis (2024-2025 Season)

This project performs an **Exploratory Data Analysis (EDA)** and **Predictive Modeling** on the **2024-2025 NBA Player Statistics** dataset. The goal is to explore the relationships between various player statistics and perform predictive analysis, particularly focusing on **points scored** by players. The project also includes **outlier detection** for points scored by players in the season.

## Project Features:
- **Data Cleaning**: Handling missing values, removing duplicates, and ensuring the dataset is ready for analysis.
- **Exploratory Data Analysis (EDA)**:
  - Distribution of points scored by players.
  - Correlation between various player statistics.
  - Visualizations to understand player performance trends.
- **Outlier Detection**:
  - Calculation of outliers for points scored by players using statistical methods (e.g., IQR or Z-score).
- **Predictive Modeling**:
  - Linear regression model to predict points scored based on other performance metrics (e.g., assists, rebounds, steals).
  
## Data Description:
The dataset contains individual player statistics for the **2024-2025 NBA season**. Key attributes include:
- **Player Name**
- **Team**
- **Games Played (GP)**
- **Points (PTS)**
- **Assists (AST)**
- **Rebounds (TRB)**
- **Steals (STL)**
- **Blocks (BLK)**
- **Minutes Played (MIN)**
- and more...

## Outlier Detection for Points Scored:
Outliers in the dataset were detected for the **points scored** attribute using statistical methods:
- **Interquartile Range (IQR)**: The IQR method was used to identify players who scored significantly more or fewer points than the majority of players in the dataset. Players with points outside the IQR bounds were flagged as outliers.
- **Visualizations**: Boxplots and histograms were used to visualize the distribution and identify outliers visually.
