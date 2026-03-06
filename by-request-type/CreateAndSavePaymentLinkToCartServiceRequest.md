# CreateAndSavePaymentLinkToCartServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.CreateAndSavePaymentLinkToCartServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** cart
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateAndSavePaymentLinkToCartRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateAndSavePaymentLinkToCartRequestHandler.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidatePayByLinkTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `CreatePaymentLinkParameters` | CreatePaymentLinkParameters |
| `string` | CartId |
| `long?` | CartVersion |
