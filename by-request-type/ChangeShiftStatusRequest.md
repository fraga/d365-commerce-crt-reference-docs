# ChangeShiftStatusRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.ChangeShiftStatusRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** employee
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Norway.XZReports.XZReportsNorwayService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Norway.XZReports.XZReportsNorwayService.md)
- [Microsoft.Dynamics.Commerce.Runtime.Workflow.ChangeShiftStatusRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.ChangeShiftStatusRequestHandler.md)
- [Microsoft.Dynamics.Commerce.Runtime.XZReportsNorway.XZReportsNorwayService (Microsoft.Dynamics.Commerce.Runtime.XZReportsNorway.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.XZReportsNorway.XZReportsNorwayService.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowsAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `string` | TerminalId |
| `long` | ShiftId |
| `string` | ShiftTerminalId |
| `ShiftStatus` | ToStatus |
| `bool` | CanForceClose |
| `string` | TransactionId |
| `bool` | HasOfflinePendingTransactions |
