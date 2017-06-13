# Stock Data
A repo containing stock data for research.
The files format follows the following structure: **$Ticker_$Candle($StartDate-$EndDate)**

- $Ticker: Symbol of the ticker ex: AAPL
- $CandleTimeFrame:
   - XM: X minute interval (ex: 5M)
   - XH: X hour interval (ex: 1H)
   - XD: X day interval (ex: 1D)
- $StartDate: Start Date (DDMMYYYY)
- $EndDate: End Date (DDMMYYYY)

To generate some quick indicators for your models, I recommend [TA-lib](http://mrjbq7.github.io/ta-lib/).
