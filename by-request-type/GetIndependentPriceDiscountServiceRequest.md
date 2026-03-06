# GetIndependentPriceDiscountServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetIndependentPriceDiscountServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** pricing
**Inherits:** ServiceRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.PricingService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.PricingService.md)

## Properties

| Type | Name |
|------|------|
| `SalesTransaction` | Transaction |
| `bool` | CalculateForNewSalesLinesOnly |
| `HashSet<string>` | NewSalesLineIdSet |
| `DateTimeOffset?` | DateWhenActive |
| `bool` | IncludeAttainablePricesAndDiscounts |
