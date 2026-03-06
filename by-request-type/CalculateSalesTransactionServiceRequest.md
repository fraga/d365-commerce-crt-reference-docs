# CalculateSalesTransactionServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateSalesTransactionServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** order
**Inherits:** ServiceRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.CartService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.CartService.md)

## Properties

| Type | Name |
|------|------|
| `SalesTransaction` | Transaction |
| `DiscountCalculationMode?` | DiscountCalculationMode |
| `bool?` | CalculateSimpleDiscountOnly |
| `CalculationModes?` | CalculationMode |
| `bool` | CalculatePricesForNewSalesLinesOnly |
| `HashSet<string>` | NewSalesLineIdSet |
