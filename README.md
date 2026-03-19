# Pandas-And-Visualization
This project explores the Google Play Store dataset to identify a market opportunity for a new mobile app focused on sustainable tourism, wellness and editorial content.
# Google Play Store Analysis — Sustainable Tourism App

## Objective
This project analyzes the Google Play Store dataset to identify market opportunities
for a new app combining sustainable tourism, wellness and editorial content.
The analysis is built on real market data to support a concrete, data-driven business proposal.

## Dataset
- `googleplaystore.csv` — 10,000+ apps with rating, installs, price, category, size
- `googleplaystore_user_reviews.csv` — user reviews with sentiment scores

Source: [Kaggle — Google Play Store Apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

## Repository Structure
```
/
├── README.md
├── googleplaystore_analysis.ipynb
├── data/
│   ├── googleplaystore.csv
│   └── googleplaystore_user_reviews.csv
└── requirements.txt
```

## How to Run
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook: `jupyter notebook googleplaystore_analysis.ipynb`

## Key Findings
- Communication and Productivity genres dominate in total downloads, but are highly saturated
- Travel & Local and News & Magazines show below-average ratings — a signal of unmet user expectations
- Health & Fitness has a more evenly distributed download base, with solid and growing demand
- Over 90% of apps in all three target categories are free — freemium is the market standard
- Engagement metric (reviews/installs ratio) reveals which categories generate the most active user communities

## Business Proposal
A freemium app combining sustainable travel guides, wellness content and editorial articles.
Target: 100,000 downloads in the first year, based on median install benchmarks in the Travel category.
Monetization: in-app purchases, premium subscription, eco-certified partner integrations.

## Libraries
- pandas, numpy
- matplotlib, seaborn
- plotly
