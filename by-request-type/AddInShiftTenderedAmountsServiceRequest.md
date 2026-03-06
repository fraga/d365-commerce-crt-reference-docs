# AddInShiftTenderedAmountsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AddInShiftTenderedAmountsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** payment
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.StoreOperationService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.StoreOperationService.md)

## Properties

| Type | Name |
|------|------|
| `string` | TerminalId |
| `long` | ShiftId |
| `ICollection<ShiftTenderLine>` | TenderLines |
