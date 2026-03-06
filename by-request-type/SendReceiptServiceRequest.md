# SendReceiptServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SendReceiptServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** order
**Inherits:** ServiceRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.EmailReceiptService (Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.EmailReceiptService.md)

## Properties

| Type | Name |
|------|------|
| `SalesOrder` | SalesOrder |
| `ReadOnlyCollection<ReceiptType>` | ReceiptTypes |
| `bool` | IsCopy |
| `ReadOnlyCollection<ElectronicAddress>` | RecipientAddresses |
