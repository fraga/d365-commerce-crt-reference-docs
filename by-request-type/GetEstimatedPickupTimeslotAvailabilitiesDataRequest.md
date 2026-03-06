# GetEstimatedPickupTimeslotAvailabilitiesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEstimatedPickupTimeslotAvailabilitiesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Domain:** other
**Inherits:** DataRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PickupTimeslotSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PickupTimeslotSqlServerDataService.md)

## Properties

| Type | Name |
|------|------|
| `string` | PickupDeliveryModeCode |
| `string` | PickupStoreId |
| `ICollection<PickupTimeslot>` | PickupTimeslots |
| `bool` | IsAdjustedForLocalTransaction |
