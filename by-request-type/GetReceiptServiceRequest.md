# GetReceiptServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Domain:** order
**Inherits:** ServiceRequest

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Services.ReceiptService (Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.ReceiptService.md)
- [Microsoft.Dynamics.Commerce.Runtime.XZReportsAustria.XZReportsAustriaService (Microsoft.Dynamics.Commerce.Runtime.XZReportsAustria.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.XZReportsAustria.XZReportsAustriaService.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Localization.Services.France.XZReports.GetReceiptServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)
- Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Austria.XZReports.XZReportsAustriaService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)
- Microsoft.Dynamics.Commerce.Runtime.XZReportsFrance.GetReceiptServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.XZReportsFrance.dll)

## Properties

| Type | Name |
|------|------|
| `SalesOrder` | SalesOrder |
| `NonSalesTransaction` | NonSalesTenderTransaction |
| `DropAndDeclareTransaction` | DropAndDeclareTransaction |
| `Shift` | ShiftDetails |
| `ReadOnlyCollection<ReceiptType>` | ReceiptTypes |
| `bool` | IsCopy |
| `bool` | IsPreview |
| `ReadOnlyCollection<TenderLine>` | TenderLines |
| `string` | HardwareProfileId |
| `bool` | IncludeExternalReceipt |
| `ReceiptType` | RequestedReceiptType |
