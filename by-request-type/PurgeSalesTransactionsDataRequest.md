# PurgeSalesTransactionsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.PurgeSalesTransactionsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Domain:** order
**Inherits:** DataRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.SalesTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.SalesTransactionSqlServerDataService.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Triggers.PurgeSalesTransactionsDataTrigger (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
- Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Norway.AuditEvent.PurgeSalesTransactionsDataTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)
- Microsoft.Dynamics.Commerce.Runtime.RegisterAuditEventNorway.PurgeSalesTransactionsDataTrigger (Microsoft.Dynamics.Commerce.Runtime.RegisterAuditEventNorway.dll)

## Properties

| Type | Name |
|------|------|
| `long` | ChannelId |
| `string` | TerminalId |
| `int` | RetentionDays |
