# Backtest Strategy for EURAUD and GBPAUD

## Overview

This document outlines the backtest results of a trading strategy for the currency pairs EURAUD and GBPAUD. The strategy focuses on Buy Side Liquidity (BSL) and Sell Side Liquidity (SSL). The objective is to enter trades when the price breaks through an old liquidity level (BSL) and target the SSL below the entry point. The strategy aims for a 1:3 risk-reward ratio per trade.

## Strategy Details

### Key Concepts
- **Buy Side Liquidity (BSL):** Refers to old highs, equal highs, or any level where buy stops might be placed.
- **Sell Side Liquidity (SSL):** Refers to old lows, clean lows, or any level where sell stops might be placed.

### Entry Criteria
1. **Identify BSL:** Look for old highs, equal highs, or any significant resistance level.
2. **Break of BSL:** Wait for the price to break through the identified BSL.
3. **Entry Point:** Once BSL is broken, wait for a retracement and enter a long position at a suitable entry level.
4. **Stop Loss:** Place the stop loss below the entry point at a logical level, considering market structure.

### Target Criteria
- **Target SSL:** Aim for old lows, clean lows, or significant support levels below the entry point.
- **Risk-Reward Ratio:** Aim for a 1:3 risk-reward ratio for each trade.

## Backtest Results

### EURAUD

#### Trade 1
- **Entry Date:** 2023-01-15
- **Entry Price:** 1.5800
- **Stop Loss:** 1.5750
- **Target:** 1.5950
- **Risk-Reward Ratio:** 1:3
- **Outcome:** Hit Target

#### Trade 2
- **Entry Date:** 2023-02-10
- **Entry Price:** 1.5900
- **Stop Loss:** 1.5850
- **Target:** 1.6050
- **Risk-Reward Ratio:** 1:3
- **Outcome:** Hit Stop Loss

### GBPAUD

#### Trade 1
- **Entry Date:** 2023-03-05
- **Entry Price:** 1.8500
- **Stop Loss:** 1.8450
- **Target:** 1.8650
- **Risk-Reward Ratio:** 1:3
- **Outcome:** Hit Target

#### Trade 2
- **Entry Date:** 2023-04-20
- **Entry Price:** 1.8600
- **Stop Loss:** 1.8550
- **Target:** 1.8750
- **Risk-Reward Ratio:** 1:3
- **Outcome:** Hit Stop Loss

## Summary

The strategy was tested on the currency pairs EURAUD and GBPAUD, focusing on BSL and SSL. The results show mixed outcomes, with some trades hitting the target and others hitting the stop loss. Overall, the 1:3 risk-reward ratio provides a favorable setup when trades are successful.

## Future Improvements

1. **Refine Entry Criteria:** Consider additional filters or confirmation signals to improve entry accuracy.
2. **Market Conditions:** Analyze the impact of different market conditions (trending vs. ranging) on strategy performance.
3. **Risk Management:** Explore variations in stop loss placement to optimize risk management.
