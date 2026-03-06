# CalculateTaxCodeTaxExclusiveAmountServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateTaxCodeTaxExclusiveAmountServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** tax
**Inherits:** ServiceRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.TaxService.md)
- [Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxServiceBrazilRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxServiceBrazilRequestHandler.md)

## Properties

| Type | Name |
|------|------|
| `TaxCode` | TaxCode |
| `ReadOnlyCollection<TaxCode>` | TaxCodes |
| `TaxableItem` | TaxableEntity |
| `ReadOnlyCollection<SalesLine>` | ActiveSalesLines |
| `decimal` | IntervalBasis |
| `bool` | IsTaxInStoreCurrency |
