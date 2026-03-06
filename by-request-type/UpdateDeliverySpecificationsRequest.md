# UpdateDeliverySpecificationsRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateDeliverySpecificationsRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** shipping
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.UpdateDeliverySpecificationsRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.UpdateDeliverySpecificationsRequestHandler.md)

## Properties

| Type | Name |
|------|------|
| `string` | CartId |
| `DeliverySpecification` | DeliverySpecification |
| `IEnumerable<LineDeliverySpecification>` | LineDeliverySpecifications |
| `bool` | UpdateOrderLevelDeliveryOptions |
| `SalesTransaction` | ExistingCart |
