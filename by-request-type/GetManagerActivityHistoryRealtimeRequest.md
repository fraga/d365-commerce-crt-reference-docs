# GetManagerActivityHistoryRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetManagerActivityHistoryRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Domain:** other
**Inherits:** RealtimeRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.EmployeeRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.EmployeeRealtimeService.md)

## Properties

| Type | Name |
|------|------|
| `string[]` | StoreIds |
| `EmployeeActivityType[]` | EmployeeActivityTypes |
| `string[]` | BreakActivities |
| `DateTimeOffset?` | FromUtcDateTime |
| `DateTimeOffset?` | ToUtcDateTime |
| `PagingInfo` | PagingInfo |
| `SortingInfo` | SortingInfo |
