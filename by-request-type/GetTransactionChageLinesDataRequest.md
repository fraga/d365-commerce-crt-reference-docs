# GetTransactionChageLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTransactionChageLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Domain:** other
**Inherits:** DataRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ChargeSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ChargeSqlServerDataService.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SalesTransactionDataServiceTriggers (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll)
- Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.Triggers.SalesTransactionDataServiceTriggers (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)

## Properties

| Type | Name |
|------|------|
| `string` | DataAreaId |
| `string` | TransactionId |
| `decimal?` | SalesLineNumber |
