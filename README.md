# Calculate Crypto Bases for Tax Reporting

These Jupyter notebooks are a pipeline for calculating the bases of your crypto transactions. You can then use these bases for reporting your capital gains or losses to the IRS.

The data source has some manual steps since the purely automatic solutions provided by [Koinly](https://koinly.io/) or [CoinTracker](https://cointracker.io) always seem to have gaps.

# Instructions

1. `pip install -r requirements.txt`
1. Run the first notebook to clean up your transactions from Etherscan.
2. Copy the cleaned-up transactions into `input/transactions.xlsx`
3. Run the second notebook to produce your report

# Status

This code is currently limited to one currency and a few data sources, but is scalable depending on how comprehensive or high-resolution you want your reporting to be.