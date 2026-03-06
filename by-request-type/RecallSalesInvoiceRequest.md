# RecallSalesInvoiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.RecallSalesInvoiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** other
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.RecallSalesInvoiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.RecallSalesInvoiceRequestHandler.md)

## Properties

| Type | Name |
|------|------|
| `string` | TransactionId |
| `string` | InvoiceId |
| `IEnumerable<long>` | InvoiceLineIds |
| `IEnumerable<RecallInvoicedSalesLineLookup>` | InvoiceLinesLookup |
| `bool` | IsReturnOrderReasonCodeRequired |
