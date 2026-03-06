# SaveStockCountRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStockCountRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** inventory
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveStockCountRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveStockCountRequestHandler.md)

## Properties

| Type | Name |
|------|------|
| `string` | JournalId |
| `ReadOnlyCollection<StockCountJournalTransaction>` | StockCountJournalTransactionList |
| `bool` | IsCommitted |
