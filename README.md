# Statistical Projects Portfolio

This repository contains a collection of data analysis and statistical projects completed using Python, Excel, and Tableau. Each folder below contains a standalone project with data, code, and visualizations.

## Projects

🔹 [Fitlife Project](https://github.com/Eriyon24/statistical-projects-README.md/blob/main/Fitlife.ipynb)  
Predicting gym membership churn using logistic regression and decision trees.

Key Findings
Note: This project uses the FitLife dataset, which is artificial/simulated. Results do not reflect real-world patterns but demonstrate statistical analysis and visualization skills.

Steps vs Calories:
Weak negative correlation (-0.12). More steps did not always mean more calories burned, likely because non-step activities (e.g., swimming, cycling) still burn calories.

Sleep vs Daily Steps:
Correlation was almost zero (0.00). Sleep hours did not predict daily activity levels — people could sleep longer but still take fewer steps if they chose low-step workouts.

Day of Week Activity:
Average steps varied by day. Some days (e.g., weekends) showed higher activity, while others (e.g., weekdays) were lower. This highlights behavioral patterns in activity scheduling.

✅ Takeaway:
Even with artificial data, this analysis shows how to:

Clean and process time-series health data

Use correlation and scatterplots for relationship testing

Group by categories (day of week) to find behavioral trends


<br><br>


🔹 [🎬 Movie Ratings Analysis](https://github.com/Eriyon24/statistical-projects-README.md/blob/main/Movie_Project.ipynb)  

🔹 Project Overview

This project uses the MovieLens Movie Rating Dataset
 to explore movie ratings and audience preferences. The analysis focused on:

Overall rating distributions

Most/least popular and highest/lowest rated movies

Genre-level insights

Statistical testing of genre differences

🔹 Methods

Data Preparation

Loaded and merged movies + ratings data

Cleaned titles to extract release years

Expanded genres for per-genre analysis

Exploratory Analysis

Average ratings, popularity counts, and distributions

Genre-wise aggregation of ratings

Visualizations (histograms, bar charts)

Statistical Testing

Conducted a t-test to compare Action vs Romance movie ratings

🔹 Key Findings

Average Rating (all movies):

3.21 / 5

Highest Rated Movie:

🎥 Sonic Outlaws (1995)

Avg. Rating: 5.0 (⚠️ only 3 ratings)

Lowest Rated Movie:

🎥 Bang (1995)

Avg. Rating: 0.5 (⚠️ only 2 ratings)

Most Popular Movie (by number of ratings):

🎥 Pulp Fiction (1994) with 3,320 ratings

Distribution of Ratings:


Most movies scored between 2.5 and 4.0, with few extremes.

Genre Analysis:


Film-Noir, Documentary, War had the highest averages (>3.4)

Horror and Sci-Fi scored lower (~2.7–3.0)

Action vs Romance (t-test):

p < 0.05 → Romance movies were rated significantly higher than Action

🔹 Takeaway

Popularity ≠ quality: The most popular movies (e.g., Pulp Fiction) were not necessarily the highest rated.

Sample size matters: Extreme highs/lows often came from very few ratings.

Genres drive ratings: Niche genres often scored better than mainstream ones.

Statistical inference strengthens insights: T-tests confirm differences between genres are meaningful.

🔹 Skills Demonstrated

Data wrangling (merging, cleaning, parsing years/genres)

Exploratory statistics (averages, distributions, counts)

Visualization (matplotlib / pandas plotting)

Statistical inference (hypothesis testing with t-tests)



<br><br>


[📊 Web Analytics A/B Testing Project](https://github.com/Eriyon24/statistical-projects-README.md/blob/main/Web%20Analytics.ipynb)  

🔹 Project Overview

This project analyzes an artificial (simulated) web analytics dataset containing traffic, sessions, conversions, and revenue by source/medium.
The goal was to practice A/B testing and conversion analysis, answering the question:

Does traffic source “A” or “B” perform better at converting users?

🔹 Methods

Data Cleaning

Removed commas from numeric columns (e.g., "126,870" → 126870).

Converted percentages (e.g., "71.59%") to decimals.

Handled special cases like "<0.01" in conversion rates.

Exploratory Analysis

Compared average conversion rates, bounce rates, and sessions by traffic source.

Built summary tables and visualizations to highlight performance differences.

Statistical Testing

Applied a two-proportion z-test to compare conversion rates between Source A and Source B.

Hypotheses:

H₀: Conversion rates are equal.

H₁: Conversion rates differ.

🔹 Key Findings (Artificial Data)

Conversion Rates (overall):

Source A: 1,110,513 users → 7,566 transactions → 0.68% conversion rate

Source B: 696,901 users → 2,838 transactions → 0.41% conversion rate

Statistical Test:

Two-proportion z-test returned p < 0.05, meaning the difference is statistically significant.

Source A converts significantly better than Source B.

Other Observations:

Bounce rates varied widely (some >70%).

Traffic volume did not always translate to efficiency, but Source A consistently showed stronger conversion performance.

🔹 Takeaway

Even though this dataset is artificial, the workflow demonstrates:

Cleaning and preparing messy web analytics data

Performing A/B testing with statistical significance testing

Extracting actionable insights from conversion metrics

📈 Practical Application: This same process can be applied to real-world website optimization and digital marketing campaigns to decide which design, campaign, or traffic source is most effective.

---

More projects coming soon!
