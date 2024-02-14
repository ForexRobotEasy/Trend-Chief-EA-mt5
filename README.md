# Trend Chief EA MT5

[![Forex Robot Easy](https://forexroboteasy.com)](https://forexroboteasy.com)

This is a code snippet for the Trend Chief EA MT5. The Trend Chief EA is an advanced forex algorithm designed for trend tracking. Please note that Forex Robot Easy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Parameters

- **Timeframe**: The trading timeframe (default: PERIOD_M15)
- **IndicatorName**: The name of the Trend Chief indicator (default: 'Trend Chief')

## Initialization

The `OnInit()` function is the expert initialization function. It attaches the Trend Chief indicator to the chart and checks if the indicator is found. If the indicator is not found, it displays an error message and terminates the EA.

## Tick Function

The `OnTick()` function is the expert tick function. It checks for a bullish trend by calling the `AllTrendLinesGreen()` function. If all trend lines have turned green and the price crosses the main red trend line, it initiates a buying action by calling the `Buy()` function. Similarly, it checks for a bearish trend by calling the `AllTrendLinesRed()` function. If all trend lines have turned red and the price crosses the main red trend line, it initiates a selling action by calling the `Sell()` function.

## Helper Functions

- **AllTrendLinesGreen()**: This function checks if all trend lines have turned green. The logic for this function is not implemented in the code snippet and needs to be added separately.
- **AllTrendLinesRed()**: This function checks if all trend lines have turned red. The logic for this function is not implemented in the code snippet and needs to be added separately.
- **CrossesMainTrendLine()**: This function checks if the price crosses the main red trend line. The logic for this function is not implemented in the code snippet and needs to be added separately.

## Buying and Selling

The `Buy()` function initiates the buying action. The logic for buying is not implemented in the code snippet and needs to be added separately. The `Sell()` function initiates the selling action. The logic for selling is not implemented in the code snippet and needs to be added separately.

For detailed reviews and trading results of this product, please visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/trend-chief-ea-mt5-review-advanced-forex-algorithm-for-trend-tracking/).
