# Fuel Prices

Automated Australian Institute of Petroleum (AIP) weekly retail fuel price extracts.

## Reporting scope

- Northern Territory: all currently available AIP NT retail series.
- National: all currently available AIP National retail series.
- Other states: capital city, state average and state regional average; state metropolitan average only when AIP publishes one.

## Files

- `data/Weekly Fuel Price Data/AIP_fuel_prices_formatted.xlsx`
- `data/Weekly Fuel Price Data/AIP_diesel_prices.csv`
- `data/Weekly Fuel Price Data/AIP_ulp_prices.csv`
- `data/Weekly Fuel Price Data/AIP_fuel_prices_long.csv`
- `data/Weekly Fuel Price Data/AIP_series_catalogue.csv`
- `data/Weekly Fuel Price Data/AIP_fetch_summary.csv`
- `documentation/AIP_fuel_price_pipeline_documentation.Rmd`

`AIP_fuel_prices_long.csv` is the recommended Power BI source and is designed to accumulate older weeks across runs.
