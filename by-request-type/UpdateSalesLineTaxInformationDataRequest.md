# UpdateSalesLineTaxInformationDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UpdateSalesLineTaxInformationDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll
**Domain:** tax
**Inherits:** DataRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.TaxTransGteSqlServerDataService.md)
- [Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxTransGteSqlServerDataService.md)

## Properties

| Type | Name |
|------|------|
| `string` | StoreId |
| `string` | TerminalId |
| `string` | TransactionId |
| `string` | DataAreaId |
| `IEnumerable<SalesLine>` | SalesLines |
