# ProcessPaymentLinkRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.ProcessPaymentLinkRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** payment
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.ProcessPaymentLinkRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.ProcessPaymentLinkRequestHandler.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidatePayByLinkTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `string` | CartId |
| `string` | PaymentReferenceId |
| `long?` | CartVersion |
