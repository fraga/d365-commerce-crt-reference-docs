# GetReceiptRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** order
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetReceiptRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetReceiptRequestHandler.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Triggers.GetReceiptRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
- Microsoft.Dynamics.Commerce.Runtime.Localization.Services.France.Receipts.GetReceiptRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)

## Properties

| Type | Name |
|------|------|
| `string` | TransactionId |
| `TenderLine` | TenderLine |
| `IEnumerable<FulfillmentLineParameter>` | FulfillmentLines |
| `IEnumerable<decimal>` | SalesLineNumbers |
| `TransferOrderJournal` | TransferOrderJournal |
| `ReceiptRetrievalCriteria` | ReceiptRetrievalCriteria |
| `string` | SalesId |
| `string` | PackingSlipId |
| `InventoryDocumentReceiptSearchCriteria` | InventoryDocumentReceiptSearchCriteria |
| `CustomerOrderType` | CustomerOrderType |
