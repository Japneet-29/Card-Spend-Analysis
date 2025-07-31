# Card Spend Analysis

This project uses simulated card transaction data to predict customer responses to promotional offers using logistic regression.

## Features

* Simulated synthetic dataset
* Data cleaning and encoding
* Logistic regression model (scikit-learn)
* Evaluation metrics (accuracy, confusion matrix)
* Data visualizations using Seaborn and Matplotlib
* Boxplots, heatmaps, and categorical comparisons

## Getting Started

1. Clone the repo
2. Install requirements: `pip install -r requirements.txt`
3. Run the notebook: `notebooks/offer_prediction.ipynb`

## Dataset

Synthetic dataset: `data/card_offer_data.csv`
Fields: AvgMonthlySpend, IncomeGroup, CategoryPreference, OfferType, OfferAccepted

## Visual Insights

Example: Customers in low income group are less likely to accept offers.
See plots in `plots/`.

## Model

Logistic regression model trained to predict `OfferAccepted`.
Accuracy: \~93%

## License

MIT License
