# PickAndPackOrderRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.PickAndPackOrderRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Domain:** order
**Inherits:** RealtimeRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrderService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrderService.md)

## Properties

| Type | Name |
|------|------|
| `string` | SalesId |
| `bool` | CreatePickingList |
| `bool` | CreatePackingSlip |
| `long` | ChannelId |
| `string` | InventoryLocationId |
| `IEnumerable<PickAndPackSalesLineParameter>` | SalesLineParameters |
