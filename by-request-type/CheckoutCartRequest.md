# CheckoutCartRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.CheckoutCartRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** cart
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.CheckoutCartRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.CheckoutCartRequestHandler.md)

## Properties

| Type | Name |
|------|------|
| `string` | CartId |
| `string` | ReceiptEmail |
| `IEnumerable<CartTenderLine>` | CartTenderLines |
| `TokenizedPaymentCard` | TokenizedPaymentCard |
| `string` | ReceiptNumberSequence |
| `long?` | CartVersion |
| `CheckoutLocation` | CheckoutLocation |
