# GetRetailShippingDiscountsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetRetailShippingDiscountsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Domain:** pricing
**Inherits:** DataRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PricingSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PricingSqlServerDataService.md)

## Properties

| Type | Name |
|------|------|
| `string` | DeliveryMode |
| `IEnumerable<ItemUnit>` | Items |
| `ISet<string>` | PriceGroups |
| `DateTimeOffset` | StartDate |
| `DateTimeOffset` | EndDate |
| `string` | CurrencyCode |
