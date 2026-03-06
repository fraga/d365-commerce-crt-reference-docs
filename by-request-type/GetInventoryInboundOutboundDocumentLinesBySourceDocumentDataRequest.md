# GetInventoryInboundOutboundDocumentLinesBySourceDocumentDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryInboundOutboundDocumentLinesBySourceDocumentDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Domain:** inventory
**Inherits:** DataRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService.md)

## Properties

| Type | Name |
|------|------|
| `long` | RecordId |
| `InventorySourceDocumentType` | DocumentType |
| `string` | Receiver |
| `long?` | ProductId |
| `ICollection<long>` | ProductIds |
| `string` | DocumentId |
| `string` | LocationId |
| `string` | ToLocationId |
| `InventoryJournalPosAdjustmentType?` | AdjustmentType |
| `string` | StaffId |
| `bool` | AllowInboundTransferOrderEmptyWorkline |
