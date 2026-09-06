# Google Play Store Analysis

## Objective

Analyze the Google Play Store ecosystem using Python to identify
patterns in app categories, ratings, installs, pricing, app size,
estimated revenue, and user sentiment.

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- VADER
- Plotly
- Jupyter Notebook

## Dataset

The project uses Google Play Store app and user review datasets.

- `play_store_apps.csv` — Contains information about applications,
  including category, rating, size, installs, type, price, and other attributes.
- `play_store_reviews.csv` — Contains user reviews and sentiment-related data.
- `google_play_store_analysis_summary.xlsx` — Contains analysis summary information.

## Analysis Performed

- Data cleaning and preprocessing
- Handling missing values and duplicate records
- App category distribution
- Category saturation analysis
- Rating distribution
- Average rating by category
- App size vs installs analysis
- Free vs paid app analysis
- Paid app price distribution
- Estimated revenue analysis
- User review sentiment analysis
- Sentiment distribution
- Sentiment analysis by category
- Interactive Plotly visualization

## Key Insights

1. The Google Play Store is dominated by free applications, while
   paid applications represent a much smaller portion of the dataset.

2. App categories show different levels of popularity and competition,
   with some categories containing significantly more applications
   than others.

3. Most applications have relatively positive ratings, indicating
   generally favorable user experiences.

4. App size does not have a simple direct relationship with the
   number of installs, as applications of different sizes can achieve
   high install counts.

5. User reviews contain a strong proportion of positive sentiment,
   while negative reviews highlight opportunities for improving
   application quality and user experience.

6. The analysis of pricing, installs, and ratings provides useful
   insights into potential monetization and application performance.

## Screenshots

### 1. Category Distribution
![Category Distribution](./screenshots/Category-distribution.png)

### 2. Rating Distribution
![Rating Distribution](./screenshots/Rating-distribution.png)

### 3. Size vs Installs
![Size vs Installs](./screenshots/Size-vs-installs.png)

### 4. Free vs Paid Apps
![Free vs Paid Apps](./screenshots/free-vs-paid.png)

### 5. Interactive Plotly
![Interactive Plotly](./screenshots/interactive-plotly.png)

### 6. Sentiment Distribution
![Sentiment Distribution](./screenshots/sentiment-distribution.png)

## Project Structure

```text
DataAnalytics-L2-Task4-GooglePlayStoreAnalysis/
│
├── Google_Play_Store_Analysis.ipynb
├── google_play_store_analysis_summary.xlsx
├── play_store_apps.csv
├── play_store_reviews.csv
│
├── screenshots/
│   ├── interactive-plotly.png
│   ├── sentiment-distribution.png
│   ├── free-vs-paid.png
│   ├── Size-vs-installs.png
│   ├── Rating-distribution.png
│   └── Category-distribution.png
│
└── README.md
