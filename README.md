# 🌿 Bellabeat Case Study: Wellness & Health Insights for Women

## Google Data Analytics Certificate • R • Business Intelligence

[![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)](https://www.r-project.org/)
[![Tidyverse](https://img.shields.io/badge/Tidyverse-4C6EB4?style=for-the-badge&logo=tidyverse&logoColor=white)](https://www.tidyverse.org/)
[![Google Data Analytics](https://img.shields.io/badge/Google%20Data%20Analytics-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://www.coursera.org/professional-certificates/google-data-analytics)

## 📝 Project Overview
This case study is part of the **Google Data Analytics Professional Certificate**. It analyzes real-world FitBit fitness tracker data to uncover how consumers use Bellabeat's smart devices.

The focus is on women's health and wellness: daily activity, steps, calories, sleep patterns, and sedentary behavior. The final deliverable provides **data-driven marketing strategy recommendations** to help Bellabeat grow by better engaging users and improving product features.

## 🎯 Key Results & Business Impact

| Metric                          | Finding                                      | Business Opportunity                   |
|---------------------------------|----------------------------------------------|----------------------------------------|
| 📏 **Average Daily Steps**      | 7,638 steps/day                              | Below WHO's 10,000 recommendation      |
| 🛋️ **Sedentary vs. Activity**   | Strong negative correlation (r = -0.33)      | High-impact area for health improvement|
| 😴 **Sleep Efficiency**         | >90% for most users                          | Already strong — maintain excellence   |
| 🛏️ **Time in Bed vs. Actual Sleep** | Users spend ~1 hour extra in bed        | Opportunity for sleep hygiene guidance |

> **Key Insight:** Increasing daily steps and reducing sedentary time are the biggest levers to improve user health and engagement.

## 🚀 Analysis Pipeline
Clear, reproducible workflow using R:

1. **Data Import & Cleaning**  
   Loaded 18 CSV files from the FitBit dataset, cleaned column names with `janitor`, parsed dates with `lubridate`.

2. **Data Merging & Transformation**  
   Combined daily activity, sleep, and hourly intensities into unified datasets.

3. **Exploratory Data Analysis (EDA)**  
   Visualized trends in steps, calories, sleep duration, and sedentary minutes using `ggplot2`.

4. **Insight Generation & Recommendations**  
   Translated statistical findings into actionable marketing strategies.

## 💡 Key Insights
- Higher step counts directly correlate with lower sedentary time — encouraging movement is critical.
- Users are good at falling asleep but spend excess time in bed — ideal for guided bedtime routines.
- Activity peaks mid-week and drops on weekends — perfect timing for motivational notifications.

## 🛠️ Tech Stack
- **Language**: R
- **Core Libraries**: tidyverse (dplyr, ggplot2, tidyr, readr, lubridate), janitor
- **Visualization**: ggplot2
- **Environment**: RStudio / Kaggle R Notebook

## 📁 Repository Structure
* `/notebooks`: Contains the `.ipynb` file with the full end-to-end code.
* `/visuals`: Contains evolution charts.

## 📊 Datasets
- **Source**: Public FitBit Fitness Tracker Data (30 users, 31 days)
- **Download Link**: [Kaggle - FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit)
- **Files Used**: `dailyActivity_merged.csv`, `sleepDay_merged.csv`, `hourlyIntensities_merged.csv`, etc. (18 CSV files total)

**How to Load in R (code snippet - don't forget this!):**
```r
# Example: Load main activity file
daily_activity <- read_csv("data/dailyActivity_merged.csv")

# Or if files are in a subfolder:
daily_activity <- read_csv("data/FitBit Fitness Tracker Data/dailyActivity_merged.csv")

```
**Author:** José Carriço  
**LinkedIn:** [linkedin.com/in/josé-carriço](https://www.linkedin.com/in/josé-carriço)  
**Kaggle:** [kaggle.com/joscarrio](https://www.kaggle.com/joscarrio)  

**Goal:** Transitioning to Data & AI Analyst | Focused on Risk Management & Fintech.

Feel free to fork, star, or reach out for collaborations! 🚀
