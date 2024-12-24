# IPL Performance Impact Model (IPIM)

## Overview
The **IPL Performance Impact Model (IPIM)** is a data-driven framework designed to evaluate player performances in the IPL (Indian Premier League). It leverages advanced machine learning techniques and custom metrics, including Euclidean and perpendicular distances, to assess player impact across various roles such as batters, bowlers, and all-rounders. The primary goal of this project is to provide actionable insights for IPL 2025 retention strategies and optimal team selection.

---

## Features
- **Data-Driven Insights**: Comprehensive analysis using player metrics such as strike rates, batting/bowling averages, and economy rates.
- **Impact Score Calculation**: A balanced metric combining Euclidean and perpendicular distances.
- **Role-Based Evaluations**: Separate models for batters, bowlers, and all-rounders.
- **Best XI Selection**: Identifies the top-performing players for a balanced team.
- **Retention Prediction**: Predicts players likely to be retained for IPL 2025.

---

## Methodology
1. **Data Collection**:
   - Ball-by-ball IPL 2024 data was used.
   - Key metrics include runs, wickets, strike rates, economy rates, etc.

2. **Data Preprocessing**:
   - Removal of irrelevant features (e.g., umpire names, match IDs).
   - Missing values were handled carefully to ensure reliability.

3. **Feature Engineering**:
   - Additional metrics like boundaries, maidens, and averages were calculated.
   - Min-Max normalization was applied to standardize metrics.

4. **Impact Score Calculation**:
   - **Euclidean Distance**: Measures overall performance.
   - **Perpendicular Distances**: Ensures balanced contributions across metrics.
   - Combined into a single impact score for ranking players.

5. **Selection Workflow**:
   - Players ranked by impact scores.
   - Top batters, bowlers, and all-rounders selected for the Best XI.
   - Retention predictions generated for IPL 2025.

---

## Technologies Used
- **Python**: For data preprocessing and model implementation.
- **Microsoft Power BI**: For data visualization and insights.
- **Machine Learning Algorithms**: Custom unsupervised learning model for impact scoring.

---

## Results
### Best XI Players of IPL 2024
- **Batters**: Virat Kohli, Travis Head, Sanju Samson (Captain), Nicholas Pooran, Venkatesh Iyer.
- **All-Rounders**: Sunil Narine.
- **Bowlers**: Jasprit Bumrah, Varun Chakravarthy, T Natarajan, Harshit Rana.
- **Impact Players**: Shashank Singh, Matheesha Pathirana.

### Retention Predictions for IPL 2025
- Generated based on consistency and overall performance metrics.
- Includes top batters, bowlers, and all-rounders from IPL 2024.

---

## Future Work
- **Real-Time Data Integration**: Include player form, injuries, and live performance updates.
- **Sentiment Analysis**: Assess fan engagement for retention decisions.
- **Team Dynamics Analysis**: Evaluate partnerships and bowler combinations.
- **Auction Dynamics**: Incorporate budget constraints and competing team needs.

---

## **Contact**
- **Name:** Z Mohammed Ghayaz
- **E-Mail**: [mdghayaz04@gmail.com](mailto:mdghayaz04@gmail.com)
- **LinkedIn:** [Mohammed Ghayaz | LinkedIn](https://www.linkedin.com/in/mohammed-ghayaz/)

---



