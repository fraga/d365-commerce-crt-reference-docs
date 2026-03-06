# OverrideCartLineChargeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.OverrideCartLineChargeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** cart
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.OverrideCartLineChargeRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.OverrideCartLineChargeRequestHandler.md)

## Properties

| Type | Name |
|------|------|
| `string` | CartId |
| `string` | CartLineId |
| `string` | ChargeLineId |
| `decimal` | Amount |
| `IEnumerable<ReasonCodeLine>` | ReasonCodeLines |
