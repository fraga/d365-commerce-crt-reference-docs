# SaveTenderLineRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.SaveTenderLineRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** payment
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveTenderLineRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveTenderLineRequestHandler.md)

## Properties

| Type | Name |
|------|------|
| `string` | CartId |
| `long?` | CartVersion |
| `string` | CustomerAccountNumber |
| `CartTenderLine` | TenderLine |
| `TenderLine` | PreprocessedTenderLine |
| `IEnumerable<ReasonCodeLine>` | ReasonCodeLines |
| `TenderLineOperationType` | OperationType |
