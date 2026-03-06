# GetDeliveryOptionsRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeliveryOptionsRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** shipping
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDeliveryOptionsRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDeliveryOptionsRequestHandler.md)

## Properties

| Type | Name |
|------|------|
| `string` | CartId |
| `IEnumerable<LineShippingAddress>` | LineShippingAddresses |
| `long?` | ChannelId |
| `bool` | FetchDeliveryOptionsForLines |
| `Address` | HeaderShippingAddress |
| `FilterDeliveryModeOption` | FilterOption |
| `bool` | UseChannelIdsBasedOnFulfillmentStore |
| `bool` | IgnoreLinesWithDeliveryMode |
