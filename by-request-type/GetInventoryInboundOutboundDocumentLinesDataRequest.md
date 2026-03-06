# GetInventoryInboundOutboundDocumentLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryInboundOutboundDocumentLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Domain:** inventory
**Inherits:** DataRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService.md)

## Properties

| Type | Name |
|------|------|
| `string` | DocumentId |
| `long?` | ProductId |
| `string` | LocationId |
| `ICollection<long>` | ProductIds |
| `string` | ToLocationId |
| `InventoryJournalPosAdjustmentType?` | AdjustmentTypeValue |
