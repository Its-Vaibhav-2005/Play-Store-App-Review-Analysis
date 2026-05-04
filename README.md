# Google Play Store App Success Analysis

An exploratory data analysis project on Google Play Store apps and user reviews. The notebook investigates which factors are most associated with app success, focusing on installs, ratings, app size, price, and user sentiment.

## Problem Statement

The Google Play Store contains thousands of apps across many categories. The goal of this project is to identify the factors that contribute to app success and understand how installs, ratings, pricing, app size, and user sentiment relate to each other.

## Dataset

- `Data/Play Store Data.csv`
- `Data/User Reviews.csv`

## Workflow

The analysis in `Main.ipynb` follows five phases:

1. Setup and loading
2. Data cleaning and transformation
3. Exploratory data analysis
4. Visualization
5. Insights and conclusion

## Key Findings

- Installs and reviews are strongly related, which suggests that popular apps naturally attract more feedback.
- Free apps dominate the marketplace, making up about 92.6% of the dataset.
- Ratings are concentrated in the 4.0 to 4.5 range and do not strongly separate app success.
- App size and price have weak relationships with installs and reviews.
- User sentiment is mostly positive, with positive reviews making up about 64% of the review set.

## Visualizations

### Rating Distribution

![Distribution of App Ratings](src/AppRatingDistribution.png)

### Correlation Heatmap

![Correlation Heatmap](src/Heatmap.png)

### Free vs Paid Apps

![Free vs Paid Apps](src/FreeVSPaid.png)

### Sentiment Distribution

![Sentiment Distribution](src/SentimentDistribution.png)

### Top Categories by Average App Size

![Top 10 Categories by Average App Size](src/Top10CategorybyAvgSize.png)

### Top Categories by Count of Apps

![Top 10 Categories by Count of Apps](src/Top10CategorybyCount.png)

### Top Categories by Installs

![Top 10 Categories by Total Installs](src/Top10CategorybyInstall.png)

### Top Categories by Sentiment

![Top 10 Categories by Sentiment](src/Top10CategorybySentiments.png)

## Repository Contents

- `Main.ipynb` - full analysis notebook
- `Data/` - source CSV files
- `src/` - exported charts used in this report

## Conclusion

App success in the Google Play Store appears to depend more on category demand and user engagement than on technical properties such as app size, price, or rating alone. Free apps and high-demand categories such as Games and Communication lead in installs, while user sentiment remains largely positive across the dataset.
