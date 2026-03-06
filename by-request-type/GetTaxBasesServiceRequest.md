# GetTaxBasesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTaxBasesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** tax
**Inherits:** ServiceRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.TaxService.md)
- [Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceIndia.TaxServiceIndiaRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceIndia.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceIndia.TaxServiceIndiaRequestHandler.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.GetTaxBasesServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll)

## Properties

| Type | Name |
|------|------|
| `TaxCode` | TaxCode |
| `ReadOnlyCollection<TaxCode>` | TaxCodes |
| `TaxableItem` | TaxableEntity |
| `ReadOnlyCollection<SalesLine>` | ActiveSalesLines |
| `decimal` | IntervalBasis |
| `bool` | CalculateBasePrice |
| `bool` | IsTaxInStoreCurrency |
| `bool` | IsTaxIncludedInPrice |
| `bool` | IsTaxExemptedForPriceInclusive |
