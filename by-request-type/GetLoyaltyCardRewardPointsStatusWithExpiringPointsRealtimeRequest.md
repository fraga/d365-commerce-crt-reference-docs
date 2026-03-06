# GetLoyaltyCardRewardPointsStatusWithExpiringPointsRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetLoyaltyCardRewardPointsStatusWithExpiringPointsRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Domain:** loyalty
**Inherits:** RealtimeRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.TransactionService.LoyaltyTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TransactionService.LoyaltyTransactionServiceRequestHandler.md)

## Properties

| Type | Name |
|------|------|
| `DateTimeOffset` | ChannelLocalDate |
| `string` | LoyaltyCardNumber |
| `bool` | ExcludeWhenBlocked |
| `bool` | ExcludeWhenNoTender |
| `bool` | IncludeRelatedCardsForContactTender |
| `bool` | IncludeNonRedeemablePoints |
| `bool` | IncludeActivePointsOnly |
| `bool` | IncludeExpiringAndUnvestedPoints |
| `int` | DaysToExpiry |
