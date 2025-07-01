# data-wrangling-nyt
Data wrangling, text cleaning, sentiment analysis, and regression modeling with New York Times comment data in R.

# Data Wrangling with NYT Comment Data

This project demonstrates real-world data wrangling, text cleaning, sentiment analysis, and regression modeling using public New York Times Cooking comment data.

## 📊 Skills Demonstrated

- Data import and exploration (`data.table`, `skimr`, `psych`)
- Data cleaning and wrangling (`dplyr`, `tidyverse`, `lubridate`)
- Text preprocessing and sentiment analysis (`qdap`, `tidytext`, `syuzhet`)
- Tokenization and stop-word removal
- Column renaming and restructuring
- Exploratory visualization (`ggplot2`, `histograms`, `plots`)
- Statistical modeling:
  - T-tests
  - Linear regressions
  - Effect visualizations
- Data merging and joins

## 🗂 Files Included

- `data-wrangling.Rmd` — Full R Markdown script with code and documentation
- `df.csv` — Raw NYT comment data
- `data-wrangling.html` — (Optional) Rendered output of the R Markdown for quick viewing

## 📚 About the Data

The dataset was collected via the New York Times Cooking API and includes public comments on recipes, along with user-generated content and interaction metrics.

Key columns:
- `commentBody`: User comment text
- `recipeName`: Name of the recipe commented on
- `sentiment`: Standardized sentiment score derived from comment text
- `replyCount`: Number of replies to the comment
- `recommendations`: Number of user likes
- Additional metadata on authors and timestamps

## 🎯 Project Overview

This project walks through:
- Cleaning messy raw data
- Renaming variables for consistency
- Filtering and subsetting data
- Exploratory text cleaning and tokenization
- Calculating standardized sentiment scores
- Visualizing distributions and relationships
- Performing t-tests comparing sentiment across recipes
- Regression analyses predicting user engagement and sentiment
- Joining multiple data sources
- Saving cleaned datasets for reproducible analysis

## 🚀 Why This Project

Practical demonstration of applied data wrangling and text analysis, essential for research and data analyst roles. Emphasizes real-world data handling, clear code documentation, and statistical modeling.

## 🛠 Requirements

- R (>= 4.x recommended)  
- R packages used: `tidyverse`, `dplyr`, `lubridate`, `qdap`, `syuzhet`, `tidytext`, `skimr`, `modelsummary`, `lme4`, etc.

## 👩🏻‍💻 Author

Annie Walsh — Social Psychologist and Data Analyst focused on applied research, data wrangling, and translating messy real-world data into insights.

---

