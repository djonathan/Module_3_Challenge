# Historical Arbitrage Opportunities in Bitcoin
### Examine trade data for arbitrage opportunities between Bitstamp and Coinbase from 2018-01-01 to 2018-03-31.
---
In a Jupyter Notebook file:
* Imported CSV data for manipulation as Python dataframes.
* Prepared the datasets for analysis by cleaning missing and erroneous data.
* Analyzed the data at a high level through summary statistics and visualizations, using this information to select  time periods in which to identify arbitrage opportunities.

---

## Technologies

Python modules used:

* pandas
* pathlib (Path())
* matplotlib.pyplot

For analysis, the **Close** values were extracted from CSV data of the form,:

    Timestamp,Open,High,Low,Close,BTC Volume,USD Volume,Weighted Price

After initial graphing of the full datasets showed higher **Close** spread in January, tapering into March, three subsets were chosen for detailed analysis:
* 2018-01-16
* 2018-02-24
* 2018-03-26

Calculations were performed to derive:
* spread
* returns
* profitable trades
* profit per trade
* cumulative profit

The resulting dataframes were examined in tabular and graphical form.

---
## Contributors

[David Jonathan](https://www.linkedin.com/in/david-jonathan-1b9470/)

---

## License

Licensed under the [MIT License](https://github.com/tmbo/questionary/blob/master/LICENSE). Copyright 2021 David Jonathan
