# UpdateChecklistTasksDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UpdateChecklistTasksDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Domain:** other
**Inherits:** DataRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ChecklistTaskSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ChecklistTaskSqlServerDataService.md)
- [Microsoft.Dynamics.Commerce.Runtime.GraphServices.PlannerTask.ChecklistTaskGraphDataService (Microsoft.Dynamics.Commerce.Runtime.GraphServices.PlannerTask.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.GraphServices.PlannerTask.ChecklistTaskGraphDataService.md)

## Properties

| Type | Name |
|------|------|
| `ICollection<ChecklistTask>` | Tasks |
| `string` | UserGraphToken |
| `long?` | ChannelId |
