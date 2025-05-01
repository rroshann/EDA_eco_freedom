# 🌍 Global Economic Freedom & Societal Outcomes

This project explores the complex relationships between economic freedom and key societal metrics such as happiness, healthcare spending, food affordability, and national wealth. Conducted as part of DS5610, the goal was to move beyond GDP and analyze how varying levels of economic liberty across countries translate into tangible quality-of-life outcomes.

## 📈 Motivation

In a globally interconnected economy, policymakers often look at economic freedom as a benchmark for prosperity. But how well does that freedom translate into actual well-being? This project investigates the nuanced, and sometimes counterintuitive, relationship between market liberty and human-centric outcomes.

## 🧩 Datasets Used

- **Economic Freedom Index (Fraser Institute)**  
- **World Happiness Report**  
- **World Bank GDP and Population Data**  
- **Healthcare Expenditure (as % of GDP)**  
- **Share of Population Unable to Afford a Healthy Diet**

## 🔍 Methodology

We used a multi-layered approach:
- **Exploratory Data Analysis (EDA)** to examine correlations between components of the Economic Freedom Index.
- **Principal Component Analysis (PCA)** for dimensionality reduction and visualization.
- **K-Means Clustering** to identify natural groupings of countries.
- **Bivariate & Multivariate Visualizations** to map freedom against outcomes like GDP per capita, food affordability, etc.

## 🌐 Key Insights

- **Trade Freedom** and **Regulatory Efficiency** were most strongly correlated with overall freedom.
- Top-performing countries formed compact, stable clusters — while fragile economies showed wider variability.
- A paradox emerged: High economic freedom does not always mean high happiness (e.g., Singapore, Hong Kong).
- Economic liberty showed stronger links to food affordability than to healthcare expenditure.
- Even among the top 10 free economies, social outcomes varied drastically depending on national policies.

## 📊 Visualizations

The project includes a suite of custom plots:
- Correlation bar plots
- PCA-based clustering maps
- Radar charts comparing cluster profiles
- Trend lines of freedom index over time
- Bubble charts comparing GDP vs. freedom
- Dual-axis charts linking freedom with food affordability

## 📌 Limitations

- Data availability was inconsistent for developing nations.
- Year 2021 was used for outcome correlations due to completeness, though it may reflect pandemic-era anomalies.
- Causal relationships were not explored — only correlations.

## 👨‍💻 Team

- Maggie Tu  
- Roshan Siddartha Sivakumar  
- Laura Li  

## 📂 Structure






- dataset

  https://worldhappiness.report/data/ (2023 -- data for table 2.1)

  https://www.fraserinstitute.org/categories/economic-freedom

  https://ourworldindata.org/grapher/happiness-cantril-ladder?tab=table&time=2015..2022&v=1&csvType=filtered&useColumnShortNames=false (Happiness - Cantril Ladder)

  https://ourworldindata.org/grapher/total-healthcare-expenditure-gdp?tab=table -- Total healthcare expenditure as a share of GDP

  https://ourworldindata.org/grapher/share-healthy-diet-unaffordable?tab=table&time=2022 -- Share of population that cannot afford a healthy diet

  https://ourworldindata.org/grapher/national-gdp-wb?tab=table&time=2021 -- Gross domestic product (GDP)

  https://ourworldindata.org/grapher/population?tab=table&time=2019..latest -- Population




- Kaggle Reference

  https://www.kaggle.com/code/farazrahman/economic-freedom-top-11-factors/notebook
  
- Documents

  Excel tracker:https://docs.google.com/spreadsheets/d/1OjiM3pMwdmNtEEC2qOmeFFIAd1Qc1jGwY1YDGOsgv-s/edit?gid=0#gid=0
  
  Report: https://docs.google.com/document/d/1VHQE4oyjy7jrVr4t6dEk9As9DN-FIC-_nNR-gEtPE7w/edit?tab=t.0
