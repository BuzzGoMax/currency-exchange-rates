[Currency Exchange Rates](https://apify.com/nexgendata/currency-exchange-rates?fpr=data)

# Currency Exchange Rates: Real-Time and Historical FX Data for 170+ Currencies

Get live and historical currency exchange rates for 170+ world currencies. Built for financial applications, travel apps, pricing tools, and international business workflows.

## Features

- **Live rates** for 170+ world currencies updated in real-time
- **Historical data** with customizable date ranges
- **Base currency selection** to convert from any currency
- **Bulk conversion** across multiple currency pairs in a single run
- **JSON output** ready for direct integration into apps and dashboards

## Use cases

- **Financial applications**: Power currency converters, portfolio trackers, and trading tools with real-time FX data
- **E-commerce pricing**: Automatically adjust international product prices based on current exchange rates
- **Travel apps**: Show users accurate local currency conversions for trip planning
- **Accounting and invoicing**: Convert international transactions to home currency for bookkeeping
- **Market research**: Track currency movements and trends across emerging and developed markets

## Input example

```
{
  "base_currency": "USD",
  "target_currencies": ["EUR", "GBP", "JPY", "CAD"],
  "include_historical": true,
  "date_range": "2025-01-01 to 2025-03-01"
}
```

## Output example

```
{
  "base": "USD",
  "date": "2025-03-01",
  "rates": {
    "EUR": 0.9234,
    "GBP": 0.7891,
    "JPY": 150.42,
    "CAD": 1.3567
  }
}
```

## Pricing

This Actor uses pay-per-event pricing. You pay only for the data you extract with no monthly fees or subscriptions.

## Integrations

Connect Currency Exchange Rates to your workflow with Apify integrations for Zapier, Make, Google Sheets, GitHub, and more. Schedule recurring runs to keep your data fresh.

## FAQ

**How often are rates updated?**
Rates are sourced from live market data and reflect the most recent available values at the time of each run.

**What currencies are supported?**
Over 170 fiat currencies plus major cryptocurrencies including BTC, ETH, and stablecoins.

**Can I get historical rates?**
Yes. Specify a date range in the input to retrieve historical exchange rate data.

## Support

For questions or issues, open an issue on the [Actor page](https://apify.com/nexgendata/currency-exchange-rates) or contact us through Apify support.