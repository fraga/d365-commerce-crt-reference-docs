# PickAndPackOrderRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.PickAndPackOrderRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** order
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.PickAndPackOrderRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.PickAndPackOrderRequestHandler.md)

## Properties

| Type | Name |
|------|------|
| `string` | SalesId |
| `bool` | CreatePickingList |
| `bool` | CreatePackingSlip |
| `IEnumerable<PickAndPackSalesLineParameter>` | SalesLineParameters |
