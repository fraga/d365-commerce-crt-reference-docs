# Employee

## Handlers (22)

| Handler | Kind | Supported Requests |
|---------|------|--------------------|
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.EmployeeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.EmployeeDataService.md) | handler | [GetEmployeeStoresFromAddressBookDataRequest](../by-request-type/GetEmployeeStoresFromAddressBookDataRequest.md), [GetEmployeeBreakCategoriesByJobDataRequest](../by-request-type/GetEmployeeBreakCategoriesByJobDataRequest.md), [GetEmployeePermissionsDataRequest](../by-request-type/GetEmployeePermissionsDataRequest.md), [GetEmployeeNotificationSubscriptionsDataRequest](../by-request-type/GetEmployeeNotificationSubscriptionsDataRequest.md), [EmployeeLogOnStoreDataRequest](../by-request-type/EmployeeLogOnStoreDataRequest.md) (+13) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ShiftDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ShiftDataService.md) | handler | [GetShiftDataRequest](../by-request-type/GetShiftDataRequest.md), [GetShiftReconciliationLinesDataRequest](../by-request-type/GetShiftReconciliationLinesDataRequest.md), [GetShiftDataDataRequest](../by-request-type/GetShiftDataDataRequest.md), [GetLastClosedShiftDataRequest](../by-request-type/GetLastClosedShiftDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.CreateEmployeeSessionRequestHandler (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.CreateEmployeeSessionRequestHandler.md) | single_handler | [CreateEmployeeSessionDataRequest](../by-request-type/CreateEmployeeSessionDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.EmployeeSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.EmployeeSqlSharedDataService.md) | handler |  |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.ShiftSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.ShiftSqlSharedDataService.md) | handler | [DeleteShiftsDataRequest](../by-request-type/DeleteShiftsDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.EmployeeSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.EmployeeSqlServerDataService.md) | handler | [UpdateEmployeePasswordDataRequest](../by-request-type/UpdateEmployeePasswordDataRequest.md), [LogAuthenticationDataRequest](../by-request-type/LogAuthenticationDataRequest.md), [VerifyUserLockoutPolicyDataRequest](../by-request-type/VerifyUserLockoutPolicyDataRequest.md), [SaveUserCredentialsDataRequest](../by-request-type/SaveUserCredentialsDataRequest.md), [DeleteUserCredentialsDataRequest](../by-request-type/DeleteUserCredentialsDataRequest.md) (+5) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ShiftSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ShiftSqlServerDataService.md) | handler | [UpdateShiftStagingTableDataRequest](../by-request-type/UpdateShiftStagingTableDataRequest.md), [CreateShiftDataRequest](../by-request-type/CreateShiftDataRequest.md), [DeleteShiftDataRequest](../by-request-type/DeleteShiftDataRequest.md), [GetShiftRequiredAmountsPerTenderDataRequest](../by-request-type/GetShiftRequiredAmountsPerTenderDataRequest.md), [GetEndOfDayShiftDetailsDataRequest](../by-request-type/GetEndOfDayShiftDetailsDataRequest.md) (+12) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.France.ShiftDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.France.ShiftDataService.md) | handler | [GetShiftDetailsDataRequest](../by-request-type/GetShiftDetailsDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.France.Shift.ShiftFranceService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.France.Shift.ShiftFranceService.md) | handler | [CalculateShiftDetailsServiceRequest](../by-request-type/CalculateShiftDetailsServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.EmployeeLogonValidationDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.EmployeeLogonValidationDataService.md) | handler | [EmployeeIdentityValidationDataRequest](../by-request-type/EmployeeIdentityValidationDataRequest.md), [EmployeeOnStoreAddressBookValidationDataRequest](../by-request-type/EmployeeOnStoreAddressBookValidationDataRequest.md), [EmployeePermissionGroupValidationDataRequest](../by-request-type/EmployeePermissionGroupValidationDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.EmployeeRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.EmployeeRealtimeService.md) | handler | [EmployeeClockInOutRealtimeRequest](../by-request-type/EmployeeClockInOutRealtimeRequest.md), [RegisterEmployeeBreakRealtimeRequest](../by-request-type/RegisterEmployeeBreakRealtimeRequest.md), [GetEmployeeCurrentRegistrationStateRealtimeRequest](../by-request-type/GetEmployeeCurrentRegistrationStateRealtimeRequest.md), [GetEmployeeActivityHistoryRealtimeRequest](../by-request-type/GetEmployeeActivityHistoryRealtimeRequest.md), [GetManagerActivityHistoryRealtimeRequest](../by-request-type/GetManagerActivityHistoryRealtimeRequest.md) (+1) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.EmployeeService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.EmployeeService.md) | handler | [GetStoresByEmployeeServiceRequest](../by-request-type/GetStoresByEmployeeServiceRequest.md), [GetEmployeesServiceRequest](../by-request-type/GetEmployeesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.StaffAuthorizationService (Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.StaffAuthorizationService.md) | handler | [StaffAuthorizationServiceRequest](../by-request-type/StaffAuthorizationServiceRequest.md), [CreateStaffSessionServiceRequest](../by-request-type/CreateStaffSessionServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.ChangeShiftStatusRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.ChangeShiftStatusRequestHandler.md) | single_handler | [ChangeShiftStatusRequest](../by-request-type/ChangeShiftStatusRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateShiftRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateShiftRequestHandler.md) | single_handler | [CreateShiftRequest](../by-request-type/CreateShiftRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationRequestHandler.md) | single_handler | [EmployeeTimeRegistrationRequest](../by-request-type/EmployeeTimeRegistrationRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.ForceDeleteShiftRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.ForceDeleteShiftRequestHandler.md) | single_handler | [ForceDeleteShiftRequest](../by-request-type/ForceDeleteShiftRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAvailableShiftsRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAvailableShiftsRequestHandler.md) | single_handler | [GetAvailableShiftsRequest](../by-request-type/GetAvailableShiftsRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCurrentEmployeeRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetCurrentEmployeeRequestHandler.md) | single_handler | [GetCurrentEmployeeRequest](../by-request-type/GetCurrentEmployeeRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetEmployeePermissionRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetEmployeePermissionRequestHandler.md) | single_handler | [GetEmployeePermissionsRequest](../by-request-type/GetEmployeePermissionsRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.ResumeShiftRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.ResumeShiftRequestHandler.md) | single_handler | [ResumeShiftRequest](../by-request-type/ResumeShiftRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.UseExistingShiftRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.UseExistingShiftRequestHandler.md) | single_handler | [UseShiftRequest](../by-request-type/UseShiftRequest.md) |

## Triggers (7)

| Trigger | Supported Requests |
|---------|--------------------|
| Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.EmployeeLogonTriggers (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll) | [EmployeeLogOnStoreDataRequest](../by-request-type/EmployeeLogOnStoreDataRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.France.UpdateShiftStagingTableDataTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll) | [UpdateShiftStagingTableDataRequest](../by-request-type/UpdateShiftStagingTableDataRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.Triggers.EmployeeLogonTriggers (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll) | [EmployeeLogOnStoreDataRequest](../by-request-type/EmployeeLogOnStoreDataRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Workflow.DataAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll) | [GetCartsDataRequest](../by-request-type/GetCartsDataRequest.md), [GetOrderOriginatorsServiceRequest](../by-request-type/GetOrderOriginatorsServiceRequest.md), [SaveCartVersionedDataRequest](../by-request-type/SaveCartVersionedDataRequest.md), [SaveCartDataRequest](../by-request-type/SaveCartDataRequest.md), [GetIncomeExpenseAccountsDataRequest](../by-request-type/GetIncomeExpenseAccountsDataRequest.md), [GetEmployeePermissionsDataRequest](../by-request-type/GetEmployeePermissionsDataRequest.md), [GetProductListDataRequest](../by-request-type/GetProductListDataRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Workflow.ServicesAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll) | [AuthorizePaymentServiceRequest](../by-request-type/AuthorizePaymentServiceRequest.md), [SaveNonSaleTenderServiceRequest](../by-request-type/SaveNonSaleTenderServiceRequest.md), [GetNonSaleTenderServiceRequest](../by-request-type/GetNonSaleTenderServiceRequest.md), [SaveDropAndDeclareServiceRequest](../by-request-type/SaveDropAndDeclareServiceRequest.md), [CalculateTaxServiceRequest](../by-request-type/CalculateTaxServiceRequest.md), [SearchJournalTransactionsServiceRequest](../by-request-type/SearchJournalTransactionsServiceRequest.md), [GetCartServiceRequest](../by-request-type/GetCartServiceRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowsAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll) | [GetCartRequest](../by-request-type/GetCartRequest.md), [SaveCartRequest](../by-request-type/SaveCartRequest.md), [GetOrdersRequest](../by-request-type/GetOrdersRequest.md), [GetAvailableShiftsRequest](../by-request-type/GetAvailableShiftsRequest.md), [SaveCartLinesRequest](../by-request-type/SaveCartLinesRequest.md), [GetXAndZReportReceiptRequest](../by-request-type/GetXAndZReportReceiptRequest.md), [ChangeShiftStatusRequest](../by-request-type/ChangeShiftStatusRequest.md), [UpdateCustomerRequest](../by-request-type/UpdateCustomerRequest.md) (+1) |
| Microsoft.Dynamics.Commerce.Runtime.XZReportsFrance.UpdateShiftStagingTableDataTrigger (Microsoft.Dynamics.Commerce.Runtime.XZReportsFrance.dll) | [UpdateShiftStagingTableDataRequest](../by-request-type/UpdateShiftStagingTableDataRequest.md) |

## Request Types (62)

### CalculateEstimatedShippingAuthorizationAmountServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateEstimatedShippingAuthorizationAmountServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CartService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### CalculateShiftAustriaDetailsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Messages.Austria.CalculateShiftAustriaDetailsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Austria.XZReports.XZReportsAustriaSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.XZReportsAustria.XZReportsAustriaSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.XZReportsAustria.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TerminalId |
| `long` | ShiftId |

### CalculateShiftDetailsNorwayDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Messages.Norway.CalculateShiftDetailsNorwayDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Norway.XZReports.XZReportsNorwaySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.XZReportsNorway.XZReportsNorwaySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.XZReportsNorway.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `XZReportType` | ReportType |
| `string` | TerminalId |
| `long` | ShiftId |

### CalculateShiftDetailsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Messages.France.CalculateShiftDetailsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.France.Shift.ShiftFranceService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `Shift` | Shift |

### ChangeShiftStatusRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.ChangeShiftStatusRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Norway.XZReports.XZReportsNorwayService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Workflow.ChangeShiftStatusRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll), Microsoft.Dynamics.Commerce.Runtime.XZReportsNorway.XZReportsNorwayService (Microsoft.Dynamics.Commerce.Runtime.XZReportsNorway.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowsAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | TerminalId |
| `long` | ShiftId |
| `string` | ShiftTerminalId |
| `ShiftStatus` | ToStatus |
| `bool` | CanForceClose |
| `string` | TransactionId |
| `bool` | HasOfflinePendingTransactions |

### CheckEmployeePermissionServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckEmployeePermissionServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationService (Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string[]` | PermissionsToCheck |

### CreateEmployeeSessionDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateEmployeeSessionDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.CreateEmployeeSessionRequestHandler (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `bool` | AlllowMultipleTerminalSessions |
| `bool` | OverrideSessionOnOtherTerminal |

### CreateShiftRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.CreateShiftRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateShiftRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CashDrawer |
| `string` | TerminalId |
| `long?` | ShiftId |
| `bool` | IsShared |

### CreateStaffSessionServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateStaffSessionServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StaffAuthorizationService (Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `bool` | OverrideSessionOnOtherTerminal |

### EmployeeClockInOutRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.EmployeeClockInOutRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.EmployeeRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | UserId |
| `string` | TerminalId |
| `bool` | IsClockIn |

### EmployeeIdentityValidationDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EmployeeIdentityValidationDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.EmployeeLogonValidationDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | StaffId |

### EmployeeLogOnStoreDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EmployeeLogOnStoreDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.EmployeeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.EmployeeLogonTriggers (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.Triggers.EmployeeLogonTriggers (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |
| `string` | StaffId |
| `string` | PasswordHash |
| `ColumnSet` | ColumnSet |

### EmployeeOnStoreAddressBookValidationDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EmployeeOnStoreAddressBookValidationDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.EmployeeLogonValidationDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | StaffId |
| `long` | ChannelId |

### EmployeePermissionGroupValidationDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EmployeePermissionGroupValidationDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.EmployeeLogonValidationDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | StaffId |

### EmployeeTimeRegistrationRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowsAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `EmployeeActivityType` | EmployeeActivityType |
| `EmployeeActivitySearchCriteria` | EmployeeActivitySearchCriteria |
| `bool` | IsLatestActivity |
| `bool` | IsSelectStore |
| `bool` | IsManagerLogbook |

### ForceDeleteShiftDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ForceDeleteShiftDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ShiftSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ShiftId |
| `string` | TerminalId |
| `string` | TransactionId |

### ForceDeleteShiftRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.ForceDeleteShiftRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.ForceDeleteShiftRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `long` | ShiftId |
| `string` | TerminalId |
| `string` | TransactionId |

### GetAvailableShiftsRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetAvailableShiftsRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAvailableShiftsRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowsAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `ShiftStatus` | Status |
| `bool` | FilterByUserRole |
| `bool` | IncludeAllShiftsForStore |

### GetClosedAustriaShiftDetailsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Messages.Austria.GetClosedAustriaShiftDetailsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Austria.XZReports.XZReportsAustriaSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.XZReportsAustria.XZReportsAustriaSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.XZReportsAustria.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ShiftId |
| `string` | TerminalId |

### GetCriteriaToVoidTransactionsByEndOfShiftRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCriteriaToVoidTransactionsByEndOfShiftRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CartService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `long` | ShiftId |
| `string` | ShiftTerminalId |

### GetEmployeeActivityHistoryRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetEmployeeActivityHistoryRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.EmployeeRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | UserId |
| `string` | StoreNumber |
| `DateTimeOffset?` | FromUtcDateTime |
| `DateTimeOffset?` | ToUtcDateTime |
| `PagingInfo` | PagingInfo |
| `SortingInfo` | SortingInfo |

### GetEmployeeAuthorizedOnAnyStoreDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeAuthorizedOnAnyStoreDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.EmployeeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | StaffId |

### GetEmployeeAuthorizedOnStoreDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeAuthorizedOnStoreDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.EmployeeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | StaffId |

### GetEmployeeBreakCategoriesByActivityDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeBreakCategoriesByActivityDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.EmployeeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | ActivityNames |

### GetEmployeeBreakCategoriesByJobDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeBreakCategoriesByJobDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.EmployeeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | JobId |

### GetEmployeeCurrentRegistrationStateRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetEmployeeCurrentRegistrationStateRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.EmployeeRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | UserId |
| `string` | TerminalId |

### GetEmployeeIdentityByExternalIdentityRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetEmployeeIdentityByExternalIdentityRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | ExternalIdentityId |
| `string` | ExternalIdentitySubId |

### GetEmployeeNotificationSubscriptionsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeNotificationSubscriptionsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.EmployeeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | StaffId |

### GetEmployeePasswordCryptoInfoDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeePasswordCryptoInfoDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.EmployeeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |
| `string` | StaffId |

### GetEmployeePermissionGroupsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.GetEmployeePermissionGroupsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.EmployeeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | StaffId |

### GetEmployeePermissionsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeePermissionsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.EmployeeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Workflow.DataAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ColumnSet` | ColumnSet |
| `string` | StaffId |

### GetEmployeePermissionsRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.Employee.GetEmployeePermissionsRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetEmployeePermissionRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ColumnSet` | ColumnSet |
| `string` | StaffId |

### GetEmployeesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmployeesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.EmployeeService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | StaffId |

### GetEndOfDayShiftDetailsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEndOfDayShiftDetailsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ShiftSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TerminalId |
| `long` | ShiftId |
| `bool` | IsTaxInclusive |

### GetEndOfDayShiftDetailsSwedenDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEndOfDayShiftDetailsSwedenDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ShiftSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | StoreId |
| `string` | TerminalId |
| `long` | ShiftId |
| `bool` | IsTaxInclusive |

### GetExternalSubIdsByStaffIdsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetExternalSubIdsByStaffIdsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.EmployeeSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ICollection<string>` | StaffIds |

### GetLastClosedShiftDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLastClosedShiftDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ShiftDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TerminalId |

### GetOfflinePendingTransactionCountByShiftDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOfflinePendingTransactionCountByShiftDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.OfflineSyncStatsDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | ShiftTerminalId |
| `long` | ShiftId |

### GetOperationPermissionsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOperationPermissionsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.EmployeeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `RetailOperation` | OperationId |

### GetRetailStaffDefaultCommissionSalesGroupDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.GetRetailStaffDefaultCommissionSalesGroupDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.EmployeeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | StaffIds |
| `string` | DataAreaId |

### GetShiftDataDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftDataDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ShiftDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ShiftDataQueryCriteria` | Criteria |

### GetShiftDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ShiftDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TerminalId |
| `long` | ShiftId |

### GetShiftDetailsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.France.GetShiftDetailsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.France.ShiftDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TerminalId |
| `long` | ShiftId |

### GetShiftReconciliationLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftReconciliationLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ShiftDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ShiftReconciliationLineRetrievalCriteria` | Criteria |

### GetShiftReconciliationLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShiftReconciliationLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StoreOperationService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ShiftReconciliationLineRetrievalCriteria` | Criteria |

### GetShiftTransactionsCountDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftTransactionsCountDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ShiftSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TerminalId |
| `long` | ShiftId |

### GetShiftsByStatusDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftsByStatusDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ShiftSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<ShiftDataQueryCriteria>` | ShiftCriteria |

### GetStaffIdByExternalIdentityDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetStaffIdByExternalIdentityDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.EmployeeSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | ExternalIdentityId |
| `string` | ExternalIdentitySubId |

### GetStaffIdsByExternalIdentitiesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetStaffIdsByExternalIdentitiesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.EmployeeSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ICollection<EmployeeExternalIdentity>` | ExternalIdentities |

### InsertShiftTaxLineDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.InsertShiftTaxLineDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.TaxSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `DataTable` | ShiftTaxLineTable |

### RegisterEmployeeBreakRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.RegisterEmployeeBreakRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.EmployeeRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | UserId |
| `string` | TerminalId |
| `string` | JobId |

### ResumeShiftRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.ResumeShiftRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.ResumeShiftRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** ShiftRequest

| Type | Property |
|------|----------|
| `string` | CashDrawer |

### SearchEmployeesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchEmployeesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.EmployeeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | StaffIds |

### StaffAuthorizationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.StaffAuthorizationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StaffAuthorizationService (Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | StaffId |
| `RetailOperation` | RetailOperation |
| `bool` | EnforceSessionToBeOpened |

### StaffLogOnRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.StaffLogOnRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `long?` | ChannelId |
| `long?` | TerminalRecordId |
| `string` | StaffId |
| `string` | StaffPassword |

### UpdateEmployeePasswordDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UpdateEmployeePasswordDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.EmployeeSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | StaffId |
| `string` | PasswordHash |
| `string` | PasswordSalt |
| `string` | PasswordHashAlgorithm |
| `DateTimeOffset` | PasswordLastChangedDateTime |
| `AuthenticationOperation` | PasswordLastUpdatedOperation |
| `bool` | ChangePasswordAtNextLogOn |
| `string` | LegacyLocalContext |
| `string` | LegacyRegistryData2 |

### UpsertAndValidateShiftsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UpsertAndValidateShiftsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ShiftSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** ShiftDataRequest

| Type | Property |
|------|----------|
| `long?` | ShiftId |
| `string` | TerminalId |

### UserLogOnRenewalRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.UserLogOnRenewalRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `Device` | Device |
| `string` | StaffId |

### UserLogOnRenewalServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnRenewalServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationService (Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `Device` | Device |
| `string` | StaffId |

### UserLogOnServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationService (Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | StaffId |
| `string` | Password |
| `string` | Credential |
| `IDictionary<string, object>` | AdditionalAuthenticationParameters |
| `string` | GrantType |

### ValidateEmployeePasswordDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateEmployeePasswordDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.EmployeeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |
| `string` | StaffId |
| `string` | PasswordHash |

### ValidateStaffPasswordRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.ValidateStaffPasswordRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | StaffId |
| `string` | Password |
