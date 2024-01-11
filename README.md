# Training Exercise HTTP CoinMarketCap

## Description

The goal of this exercise is to implement the CoinMarketCap API calls (https://coinmarketcap.com/api/)
Before starting the exercise:

* Create a CoinMarketCap account.
* Generate an API key.
* Read the API quick start guide.
* Implement the following endpoints/call (only implement the useful columns, free to choose).
  * GET /v1/cryptocurrency/listings/latest
  * GET /v1/cryptocurrency/categories
    * Refresh button on row level for an individual category.
    * v1/cryptocurrency/category?id={CategoryId}
  * GET /v1/global-metrics/quotes/latest

## Pointers

Handle this exercise as would be for a customer.

* All parameter names/descriptions should be carefully chosen to really reflect the value.
* No errors/major/minor/... should be reported by the DIS validator.
* No magic numbers in QActions.
* Alarming and trending where needed.
* Some rules when working with tables:
  * Every column name should start with the table name.
  * Every column description has the table description between round brackets.

## Tips

* To parse the JSON use NewtonSoft.Json.
* Consider using the QActionTableRows for updating tables.
* You can test the API call with Postman before implementing.
