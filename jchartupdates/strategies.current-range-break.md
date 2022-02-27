---
id: u2rgy4mrre7pyr0j5d040kc
title: Current Range Break
desc: ''
updated: 1645993835673
created: 1645992774810
---

This strategy finds stocks based on an x day range break. The objective it to capture the trend early by identifying the first time the stock breaks out of the range. Subsequent breaks are ignored. We do this by using moving averages as filter.

### The logic

* find all stocks that have made a 50 day high
* the 10 day MA must be above the 21 Day MA
* if this is the first time the stock has made a 50 day high after the 10 day MA crossed above the 50 day MA, then this stock is added to the list

### Entry Price

Next day's opening price

### Initial stop

2 * ATR(14) below the closing price

### Exit

21 day MA break
