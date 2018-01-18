Cryptocurrency widget
=====================

This is my attempt to keep track of my current cryptocurrency portfolio. This widget is going to display the following information:
* Price of a coin in USD
* Current value of a coin in USD
* Current value of your entire portfolio in USD


How to use this widget
----------------------
In order to use this widget, you will need to create a text file located in `~/.cryptoholdings.json`
This file will contain your holdings in various coins.

Example:
```
{
    "ark": { "ticker": "ARK", "round": 2, "holdings": 2.98099 },
    "bitcoin": { "ticker": "BTC", "round": 0, "holdings": 7 },
    "litecoin": { "ticker": "LTC", "round": 2, "holdings": 5.41853337 },
}
```

NOTE: This widget is getting its data from coinmarketcap and coin name must match `id` of a coin as reported by coinmarketcap. For list of all supported coins, please visit: https://api.coinmarketcap.com/v1/ticker/
