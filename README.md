# Overlay Chart Indicator ReadMe

This ReadMe file provides an overview of the Overlay Chart Indicator code (`mql5`) and explains how it works. It also includes a product description based on the code. Please note that ForexRobotEasy is not the official developer of this product. We are only providing sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Overview

The Overlay Chart Indicator is designed to enhance currency correlation analysis by allowing traders to view the price action of different timeframes on a single chart. This code creates two overlay buffers for the specified currency pairs, `Symbol1` and `Symbol2`, and plots them on the chart window in different colors.

The indicator uses the close prices of `Symbol1` and the simple moving average (SMA) of `Symbol2` to generate the overlay buffers. The indicator buffers are then used to plot the price action on the chart.

## Indicator Parameters

- `Symbol1`: The symbol for the first currency pair (default: 'EURUSD').
- `Symbol2`: The symbol for the second currency pair (default: 'USDJPY').

## Indicator Initialization

During initialization, the indicator selects the specified currency pairs, sets the indicator buffers, and sets the indicator label.

## Indicator Deinitialization

During deinitialization, the indicator removes the indicator buffers.

## Indicator Calculation

During each calculation iteration, the indicator calculates the overlay buffers for the specified currency pairs. The close prices of `Symbol1` are stored in `OverlayBuffer1`, and the SMA of `Symbol2` is stored in `OverlayBuffer2`. The indicator uses the `OnCalculate` function to perform this calculation.

## Product Description

The Overlay Chart Indicator is a powerful tool that enhances currency correlation analysis by allowing traders to view price action of different timeframes on a single chart. By overlaying the price movements of multiple currency pairs, traders can easily identify correlations and make more informed trading decisions.

With the Overlay Chart Indicator, traders can easily compare the price movements of different currency pairs and identify patterns and trends. This can help in identifying potential trading opportunities and improving overall trading accuracy.

Key features of the Overlay Chart Indicator include:

- Customizable currency pairs: Traders can choose any two currency pairs to overlay on the chart. The default currency pairs are 'EURUSD' and 'USDJPY', but traders can easily modify them according to their preferences.
- Real-time correlation analysis: The indicator provides real-time price data, allowing traders to analyze currency correlations and make timely trading decisions.
- User-friendly interface: The indicator is easy to use and understand, making it suitable for both beginner and experienced traders.

To access detailed reviews and trading results of this product, please visit our website [Forex Robot Easy - Overlay Chart Indicator Review](https://forexroboteasy.com/forex-robot-review/overlay-chart-indicator-review-enhance-forex-trades-with-real-time-correlation/). Please note that ForexRobotEasy is not the official developer of this product. We are only providing sample code that can work as described in this product.

For more information about the official developer of this product, please visit MQL5.

For any support or inquiries, please contact Forex Robot Easy Team at [forexroboteasy.com](https://forexroboteasy.com/).
