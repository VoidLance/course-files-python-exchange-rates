# Python Exchange Rates

A small Python module containing example exchange rates from US dollars (USD)
to euros (EUR), British pounds (GBP), and Japanese yen (JPY).

## Why use this project?

- Import the exchange-rate constants directly into a Python program.
- No third-party packages or setup beyond Python are required.
- Useful as a simple learning example or starting point for currency
  conversions.

The rates in `exchange_rates.py` are fixed example values, not live market data.
They can become outdated and should not be used for financial decisions.

## Getting started

Clone the repository and change into its directory:

```bash
git clone https://github.com/VoidLance/course-files-python-exchange-rates.git
cd course-files-python-exchange-rates
```

Import a rate and multiply a USD amount to convert it:

```python
from exchange_rates import USD_TO_EUR, USD_TO_GBP, USD_TO_JPY

usd_amount = 10
eur_amount = usd_amount * USD_TO_EUR
gbp_amount = usd_amount * USD_TO_GBP
jpy_amount = usd_amount * USD_TO_JPY

print(f"€{eur_amount:.2f}")
print(f"£{gbp_amount:.2f}")
print(f"¥{jpy_amount:.2f}")
```

The available constants are `USD_TO_EUR`, `USD_TO_GBP`, and `USD_TO_JPY`.

## Help

For questions or problems, open an issue in the
[GitHub repository](https://github.com/VoidLance/course-files-python-exchange-rates/issues).

## Maintainers and contributing

No named maintainer or separate contribution guide is included in this
repository. Contributions are welcome: open an issue to discuss a change, then
submit a pull request with a focused description.
