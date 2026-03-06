# SearchInventoryInboundOutboundDocumentsByOperationTypesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchInventoryInboundOutboundDocumentsByOperationTypesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Domain:** inventory
**Inherits:** DataRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService.md)

## Properties

| Type | Name |
|------|------|
| `string` | Sender |
| `string` | Receiver |
| `IEnumerable<InventoryInboundOutboundDocumentOperationType>` | OperationTypes |
| `InventoryDocumentSearchCriteria` | SearchCriteria |
