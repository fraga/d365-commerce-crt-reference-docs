# GetStoreAvailabilityRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetStoreAvailabilityRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Domain:** channel
**Inherits:** RealtimeRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.AvailabilityTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.AvailabilityTransactionService.md)

## Properties

| Type | Name |
|------|------|
| `string` | ItemId |
| `string` | VariantId |
| `bool` | IncludeNonStoreWarehouses |
| `long` | CurrentStoreId |
| `PagingInfo` | Paging |
| `SortingInfo` | Sorting |
| `GetStoreAvailabilityRtsVersion` | VersionToCall |
| `OrgUnitAvailabilitySearchCriteria` | OrgUnitAvailabilitySearchCriteria |
