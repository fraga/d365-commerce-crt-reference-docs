# CancelCartPaymentLinkRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.CancelCartPaymentLinkRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** cart
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.CancelCartPaymentLinkHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.CancelCartPaymentLinkHandler.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidatePayByLinkTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `string` | CartId |
| `string` | PaymentReferenceId |
| `long?` | CartVersion |
