# OverrideChargeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.OverrideChargeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** pricing
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.OverrideChargeRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.OverrideChargeRequestHandler.md)

## Properties

| Type | Name |
|------|------|
| `string` | CartId |
| `string` | ChargeLineId |
| `decimal` | Amount |
| `IEnumerable<ReasonCodeLine>` | ReasonCodeLines |
