# SaveNonSaleTenderServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveNonSaleTenderServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** payment
**Inherits:** NonSaleTenderServiceRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.StoreOperationService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.StoreOperationService.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Workflow.ServicesAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `decimal` | Amount |
| `string` | Currency |
| `string` | Description |
| `string` | TenderTypeId |
| `string` | TransactionId |
| `TransactionStatus` | TransactionSatus |
| `IEnumerable<ReasonCodeLine>` | ReasonCodeLines |
| `ICollection<DenominationDetail>` | DenominationDetails |
| `decimal` | GiftCardBalance |
| `decimal` | GiftCardIssueAmount |
| `DateTimeOffset` | GiftCardActiveFrom |
| `DateTimeOffset` | GiftCardExpiryDate |
| `string` | GiftCardHistoryDetails |
| `string` | GiftCardIdMasked |
| `string` | GiftCardCurrencyCode |
| `string` | FromSafe |
| `string` | ToSafe |
| `string` | FromShiftTerminalId |
| `string` | ToShiftTerminalId |
| `string` | FromShiftId |
| `string` | ToShiftId |
| `CashManagementTransactionContext` | TransactionSourceContextType |
| `CashManagementTransactionContext` | TransactionDestinationContextType |
