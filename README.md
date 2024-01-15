# Average ATR Levels

This is a custom indicator called 'Average ATR Levels' developed by the Forex Robot Easy Team. The indicator calculates the Average True Range (ATR) and displays it on the chart along with the corresponding ATR level.

## Indicator Settings

- **Period**: The period used to calculate the ATR. The default value is 14.
- **Level Line Color**: The color of the ATR level line. The default color is Green.
- **Level Line Width**: The width of the ATR level line. The default width is 1.

## Indicator Initialization

The indicator is initialized in the `OnInit()` function. The indicator style and buffers are set using the `SetIndexStyle()` and `SetIndexBuffer()` functions. The `IndicatorSetInteger()` function is used to set the number of decimal places for the indicator.

## Indicator Calculation

The indicator calculations are performed in the `OnCalculate()` function. The function receives the price data and calculates the ATR and ATR level for each bar.

The ATR is calculated using the `iATR()` function with the specified period. The ATR values are stored in the `atrBuffer` array.

The ATR level is calculated by finding the minimum and maximum prices within the specified period and dividing the price range by the ATR value. The ATR level values are stored in the `atrLevelBuffer` array.

## Product Description

The 'Average ATR Levels' indicator is a powerful tool for volatility control in forex trading. It calculates the Average True Range (ATR) and displays it on the chart, allowing traders to assess the level of market volatility.

The indicator provides two main features:

1. Average True Range (ATR): The ATR is a measure of market volatility. It calculates the average range between the high and low prices over a specified period. Traders can use the ATR to determine the potential for price movement and adjust their trading strategies accordingly.

2. ATR Levels: The indicator also displays the ATR level on the chart. The ATR level is calculated by comparing the price range within a specified period to the ATR value. Traders can use the ATR level to identify potential support and resistance levels and make more informed trading decisions.

This product is developed by the Forex Robot Easy Team. Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Review Average ATR Levels](https://forexroboteasy.com/forex-robot-review/review-average-atr-levels-forex-software-for-volatility-control/).

## Disclaimer

Please note that trading in the forex market involves substantial risk and is not suitable for all investors. The information provided in this ReadMe file is for educational purposes only and should not be considered as financial advice. Users of this indicator should exercise caution and conduct their own research and analysis before making any investment decisions.
