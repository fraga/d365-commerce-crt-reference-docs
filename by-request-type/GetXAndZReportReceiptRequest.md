# GetXAndZReportReceiptRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetXAndZReportReceiptRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** order
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Norway.XZReports.XZReportsNorwayService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Norway.XZReports.XZReportsNorwayService.md)
- [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetXAndZReportReceiptRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetXAndZReportReceiptRequestHandler.md)
- [Microsoft.Dynamics.Commerce.Runtime.XZReportsNorway.XZReportsNorwayService (Microsoft.Dynamics.Commerce.Runtime.XZReportsNorway.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.XZReportsNorway.XZReportsNorwayService.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowsAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `string` | ShiftTerminalId |
| `long` | ShiftId |
| `ReceiptType` | ReceiptType |
| `string` | TransactionId |
| `string` | HardwareProfileId |
