Palmer Penguins – Data Exploration & Visualisation
-
COMP H2038 — IT Maths & Data Visualisation
Author: Viktoriia Bielhrad

This project explores the Palmer Penguins dataset (344 observations, 7 variables) using R. 
The analysis investigates species differences, body size relationships, sex-based variation, 
and island distribution through summary statistics and visualisations.

Data Import & Structure
-
The dataset includes categorical variables (species, island, sex) and numerical variables 
(culmen length/depth, flipper length, body mass). Initial inspection used head(), summary(),
and structural checks.

Data Quality
-
Missing values detected in culmen length/depth, flipper length, body mass, and sex.
No duplicates found.
Outliers identified via boxplots across multiple species.
Addressing these issues improves reliability and accuracy of the analysis.

Exploratory Data Analysis
-
Univariate Analysis
Histograms and boxplots reveal:
Chinstrap penguins have the largest culmen.
Gentoo penguins have the longest flippers and highest body mass.
Skewness varies across variables (positive/negative).

Bivariate Analysis
Scatterplots and correlation heatmaps show:
Strong positive correlation between flipper length and body mass.
Gentoo species form distinct clusters due to large body mass and small culmen depth.
Sex-based boxplots show males generally larger across measurements.

Species & Island Insights
-
Adelie: largest population (146).
Chinstrap: smallest population (68).
Biscoe Island hosts the most penguins; Torgersen the fewest.

Conclusions
-
The dataset reveals clear species differences, strong variable relationships, 
and meaningful patterns in size, sex, and island distribution. Visualisations 
(histograms, boxplots, bar charts, scatterplots, heatmaps) effectively highlight trends and correlations.
