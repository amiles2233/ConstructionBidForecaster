# Low-Bid Forecaster

Static web apps that forecast the winning (low) bid on public road jobs:

- `/` Texas: TxDOT lettings, built from public Texas Open Data Portal records, with a backtest.
- `/ma/` Massachusetts (early look): upcoming MassDOT jobs, forecast with a method tested on
  Rhode Island bids. Not yet tested on Massachusetts results.

This repo holds only the generated site; it is rebuilt and pushed from the private analysis
repo (`make pages`).
