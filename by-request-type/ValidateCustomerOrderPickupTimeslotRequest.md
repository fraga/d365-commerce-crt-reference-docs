# ValidateCustomerOrderPickupTimeslotRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateCustomerOrderPickupTimeslotRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** customer
**Inherits:** ServiceRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrderValidationService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrderValidationService.md)

## Properties

| Type | Name |
|------|------|
| `string` | DeliveryModeCode |
| `string` | StoreId |
| `DateTimeOffset?` | PickupDate |
| `DateTimeOffset?` | StartDateTime |
| `DateTimeOffset?` | EndDateTime |
| `SalesTransaction` | ExistingTransaction |
