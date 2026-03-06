# AdjustInventoryDocumentSerialNumberLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AdjustInventoryDocumentSerialNumberLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Domain:** inventory
**Inherits:** DataRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentTrackingDimensionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentTrackingDimensionSqlServerDataService.md)

## Properties

| Type | Name |
|------|------|
| `string` | WorkDocumentId |
| `ICollection<string>` | DocumentLineIds |
| `ICollection<InventoryDocumentSerialNumberLine>` | Lines |
