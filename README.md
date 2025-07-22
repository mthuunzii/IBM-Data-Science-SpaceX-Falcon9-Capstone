# SpaceX Falcon 9 Launch Success Prediction
🚀 A Data Science Capstone Project

## Project Overview
This project analyzes SpaceX Falcon 9 rocket launches to predict the success of first-stage landings, a critical factor in reducing launch costs. By leveraging machine learning and exploratory data analysis (EDA), we identify key factors influencing landing success and build an interactive dashboard for visualization.

## Key Questions
✔ What factors determine successful rocket landings?

✔ How do launch sites, orbits, and payloads affect success rates?

✔ Can we predict landing outcomes to optimize mission planning?

## Methodology
1. Data Collection
SpaceX REST API: Fetched historical launch data.

Web Scraping (Wikipedia): Extracted Falcon 9 launch records using BeautifulSoup.

2. Data Wrangling & EDA
Cleaned data, applied one-hot encoding, and created binary labels (0 = failure, 1 = success).

SQL Analysis: Queried PostgreSQL to analyze payloads, orbits, and launch sites.

Visualizations: Flight number vs. launch site, payload vs. orbit, yearly trends.

EDA with Visualization

3. Interactive Analytics
Folium Maps: Marked launch sites with success/failure clusters.

Plotly Dash Dashboard:

Pie charts for launch success rates.

Scatter plots for payload vs. outcome.

4. Machine Learning (Classification)
Models: Decision Tree, Logistic Regression, SVM.

Best Model: Decision Tree (highest accuracy).

Challenge: False positives (misclassified failures).

Notebook: ML Prediction

# Key Findings
1. ## Launch Success Trends
📈 Success rates increased from 2013–2020.

📍 Best Launch Site: KSC LC-39A (highest success rate).

🛰️ Top Orbits: ES-L1, GEO, HEO, SSO, VLEO.

2. ## SQL Insights
🚀 First successful ground landing: Dec 22, 2015.

⚖️ NASA’s total payload mass: 45,596 kg.

3. ## Predictive Model Performance
✅ Best Model: Decision Tree (~94% accuracy).

⚠️ Limitation: Some false positives (failures predicted as successes).
