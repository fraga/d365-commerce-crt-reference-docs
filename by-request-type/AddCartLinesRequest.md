# AddCartLinesRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.AddCartLinesRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** cart
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.AddCartLinesRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.AddCartLinesRequestHandler.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidateBusinessPartnerCatalogTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `string` | CartId |
| `IEnumerable<CartLine>` | CartLines |
| `CalculationModes?` | CalculationMode |
| `long?` | CartVersion |
