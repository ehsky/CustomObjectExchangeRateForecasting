# Custom Object Exchange Rate Forecasting

Uses the Salesforce Forecasting and Advanced Currency Management to set the exchange rate on a object of your own chosing. In this example, the object is OrderLine.
The rates are stored in the object DatedConversionRate.
One can easily clone the flow and replace with a new object and equivalent fields.

## Contains

- Flow: OrderProduct_TRG_SetExchangeRate
- Field: ConversionRate\_\_c on OrderLine
- Field: TotalPriceInCorporateCurrencie\_\_c on OrderLine

## Deploy

You can use the quick installer here to deploy the code directly to your org. \
[![Deploy to salesforce](https://githubsfdeploy.herokuapp.com/resources/img/deploy.png)](https://githubsfdeploy.herokuapp.com/?owner=ehsky&repo=Custom-Object-Exchange-Rate-Forecasting)
