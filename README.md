# 🌍 2015 World Happiness Index Analysis

## 📘 Project Overview

This project examines the 2015 World Happiness Index dataset, analyzing global patterns of happiness and their relationships to economic, social, and governance factors. Using Power BI and statistical techniques, I examined which countries report the highest happiness levels, how regional trends emerge, and what variables drive or limit subjective well-being.

## 📊 Dashboard Overview

The interactive dashboard provides:
- Country-level happiness comparisons
- Regional happiness averages
- Correlation breakdowns between happiness and key factors (GDP, social support, life expectancy, etc.)
- Governance perception metrics (trust in government, satisfaction with governance)

---

## 🔎 Key Insights

1. *Happiest Country*: Switzerland ranked #1 in global happiness.
2. *Least Happy Country*: Togo recorded the lowest happiness score.
3. *Regional Trend: Western Europe is the **happiest region, followed by **North America*.
4. *Correlation Analysis* (with overall happiness score):
   - *GDP per capita* → 0.78
   - *Family/social support* → 0.74
   - *Healthy life expectancy* → 0.72
   - *Freedom to make life choices* → 0.56
5. *Generosity disconnect: High generosity scores do **not always correlate* with higher happiness, indicating that cultural or policy factors may affect perceived well-being.
6. *Governance Concerns*:
   - Only *48% of people* globally trust their government.
   - Merely *13 out of 100 people* report being satisfied with how they are governed.
7. *Personal Hypothesis: I created a custom metric comparing **happiness scores vs governance satisfaction. Only **7%* countries show alignment between high happiness and high governance trust.

---

## ❓ Exploratory Question

### Is happiness truly tied to trust in governance?

While economic and social factors show a strong positive correlation with happiness, the *governance trust gap is significant*. In most countries:
- People report high happiness *despite* poor trust in government.
- Only a *small overlap (~7%)* exists between countries where people are both *happy* and *satisfied with governance*.

> 🔍 Conclusion: Happiness is influenced more by *economic, familial, and health factors, while **governance dissatisfaction* is tolerated or offset in otherwise strong environments (e.g., Western Europe).

---

## 💡 Recommendations & Reflections

- Policymakers should not rely solely on GDP; *life expectancy, family networks, and freedom* are equally critical.
- Governments must focus on *restoring trust* and *accountability*, as a large gap exists between governance performance and population happiness.
- Future indices could include *qualitative well-being measures*, such as emotional safety, access to justice, or democratic participation.

---

## 💼 Tools & Techniques

- *Power BI* – for dashboard development and interactive exploration
- *Excel & DAX* – for custom calculations and statistical correlation
- *Manual index scoring* – for governance comparison

—
## 📊 Analytical Approach

- *Data Cleaning & Preparation*: Standardized country names, handled missing values, and normalized key metrics for fair comparison.
- *Regional Aggregation*: Grouped countries by geographic region to assess regional happiness patterns and trends.
- *Correlation Analysis*: Used statistical techniques (Pearson correlation) to measure the strength of association between happiness and influencing factors like GDP, family support, life expectancy, freedom, and generosity.
- *Custom Scoring*: Created a custom governance satisfaction index based on trust in government and perceived governance quality, then compared it with the global happiness index to explore alignment.
- *Dashboard Development*: Designed an interactive Power BI dashboard with slicers and visual storytelling to highlight top/least happy countries, correlation patterns, and the governance gap.


__

## 📊 Detailed Visual Analysis

# C1: Regional Happiness Averages
Western Europe leads, followed by North America. Sub-Saharan Africa remains the lowest.




# C2: Governance vs Happiness Gap
Only a handful of countries exhibit high governance satisfaction *and* high happiness. Most are disconnected.




# C3: Correlation Matrix with Happiness
Strongest correlations are with GDP (0.78), family (0.74), and life expectancy (0.72).
