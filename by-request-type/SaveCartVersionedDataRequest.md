# SaveCartVersionedDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveCartVersionedDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Domain:** cart
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.SalesTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.SalesTransactionSqlServerDataService.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Triggers.SaveCartVersionedDataRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
- Microsoft.Dynamics.Commerce.Runtime.Workflow.DataAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `SalesTransaction` | SalesTransaction |
| `bool` | IgnoreVersionCheck |
| `TransactionOperationType` | OperationType |
