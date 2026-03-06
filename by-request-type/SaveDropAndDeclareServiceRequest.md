# SaveDropAndDeclareServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveDropAndDeclareServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** other
**Inherits:** ServiceRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.StoreOperationService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.StoreOperationService.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Workflow.ServicesAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `TransactionType` | TransactionType |
| `ExtensibleTransactionType` | ExtensibleTransactionType |
| `IEnumerable<TenderDetail>` | TenderDetails |
| `IEnumerable<ReasonCodeLine>` | ReasonCodeLines |
| `string` | ShiftId |
| `string` | ShiftTerminalId |
| `string` | TransactionId |
| `DateTimeOffset` | BeginDateTime |
| `string` | Description |
| `TransactionStatus` | TransactionSatus |
| `string` | FromSafe |
| `string` | ToSafe |
| `string` | FromShiftTerminalId |
| `string` | ToShiftTerminalId |
| `string` | FromShiftId |
| `string` | ToShiftId |
| `CashManagementTransactionContext` | TransactionSourceContextType |
| `CashManagementTransactionContext` | TransactionDestinationContextType |
