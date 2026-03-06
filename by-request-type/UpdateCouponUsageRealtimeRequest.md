# UpdateCouponUsageRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.UpdateCouponUsageRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Domain:** pricing
**Inherits:** RealtimeRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.TransactionService.CouponTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TransactionService.CouponTransactionServiceRequestHandler.md)

## Properties

| Type | Name |
|------|------|
| `IEnumerable<string>` | CouponCodeIds |
| `string` | CustomerAccount |
| `long` | ChannelId |
| `string` | TransactionId |
| `string` | ReceiptId |
| `string` | SalesId |
| `CouponUsageStatus` | Status |
| `bool` | IsValidationRequired |
