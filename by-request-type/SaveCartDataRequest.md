# SaveCartDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveCartDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Domain:** cart
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.SalesTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.SalesTransactionSqlServerDataService.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Workflow.DataAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `IEnumerable<SalesTransaction>` | SalesTransactions |
| `bool` | IgnoreRowVersionCheck |
