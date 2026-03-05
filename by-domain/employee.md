# Employee

## Handlers (20)

| Handler | Kind | Assembly | Supported Requests |
|---------|------|----------|--------------------|
| ChangeShiftStatusRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | ChangeShiftStatusRequest |
| CreateEmployeeSessionRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | CreateEmployeeSessionDataRequest |
| CreateShiftRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | CreateShiftRequest |
| EmployeeDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetEmployeeStoresFromAddressBookDataRequest, GetEmployeeBreakCategoriesByJobDataRequest, GetEmployeePermissionsDataRequest, GetEmployeeNotificationSubscriptionsDataRequest, EmployeeLogOnStoreDataRequest (+13) |
| EmployeeLogonValidationDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | EmployeeIdentityValidationDataRequest, EmployeeOnStoreAddressBookValidationDataRequest, EmployeePermissionGroupValidationDataRequest |
| EmployeeRealtimeService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | EmployeeClockInOutRealtimeRequest, RegisterEmployeeBreakRealtimeRequest, GetEmployeeCurrentRegistrationStateRealtimeRequest, GetEmployeeActivityHistoryRealtimeRequest, GetManagerActivityHistoryRealtimeRequest (+1) |
| EmployeeService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll | GetStoresByEmployeeServiceRequest, GetEmployeesServiceRequest |
| EmployeeSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | UpdateEmployeePasswordDataRequest, LogAuthenticationDataRequest, VerifyUserLockoutPolicyDataRequest, SaveUserCredentialsDataRequest, DeleteUserCredentialsDataRequest (+5) |
| EmployeeTimeRegistrationRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | EmployeeTimeRegistrationRequest |
| ForceDeleteShiftRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | ForceDeleteShiftRequest |
| GetAvailableShiftsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetAvailableShiftsRequest |
| GetCurrentEmployeeRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetCurrentEmployeeRequest |
| GetEmployeePermissionRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetEmployeePermissionsRequest |
| ResumeShiftRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | ResumeShiftRequest |
| ShiftDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetShiftDataRequest, GetShiftReconciliationLinesDataRequest |
| ShiftDataService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll | GetShiftDetailsDataRequest |
| ShiftFranceService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | CalculateShiftDetailsServiceRequest |
| ShiftSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | UpdateShiftStagingTableDataRequest, CreateShiftDataRequest, GetShiftDataDataRequest, DeleteShiftDataRequest, GetShiftRequiredAmountsPerTenderDataRequest (+15) |
| StaffAuthorizationService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll | StaffAuthorizationServiceRequest, CreateStaffSessionServiceRequest |
| UseExistingShiftRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | UseShiftRequest |

## Triggers (7)

| Trigger | Assembly | Supported Requests |
|---------|----------|--------------------|
| DataAuthorizationTrigger | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetCartsDataRequest, GetOrderOriginatorsServiceRequest, SaveCartVersionedDataRequest, SaveCartDataRequest, GetIncomeExpenseAccountsDataRequest, GetEmployeePermissionsDataRequest, GetProductListDataRequest |
| EmployeeLogonTriggers | Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll | EmployeeLogOnStoreDataRequest |
| EmployeeLogonTriggers | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | EmployeeLogOnStoreDataRequest |
| ServicesAuthorizationTrigger | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | AuthorizePaymentServiceRequest, SaveNonSaleTenderServiceRequest, GetNonSaleTenderServiceRequest, SaveDropAndDeclareServiceRequest, CalculateTaxServiceRequest, SearchJournalTransactionsServiceRequest, GetCartServiceRequest |
| UpdateShiftStagingTableDataTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll | UpdateShiftStagingTableDataRequest |
| UpdateShiftStagingTableDataTrigger | Microsoft.Dynamics.Commerce.Runtime.XZReportsFrance.dll | UpdateShiftStagingTableDataRequest |
| WorkflowsAuthorizationTrigger | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetCartRequest, SaveCartRequest, GetOrdersRequest, GetAvailableShiftsRequest, SaveCartLinesRequest, GetXAndZReportReceiptRequest, ChangeShiftStatusRequest, UpdateCustomerRequest, EmployeeTimeRegistrationRequest |
