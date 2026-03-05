# Sync

## Handlers (11)

| Handler | Kind | Assembly | Supported Requests |
|---------|------|----------|--------------------|
| AsynchronousWorkflowService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll | DeleteAsynchronousWorkflowRequest, GetAsynchronousWorkflowRequest, SaveAsynchronousWorkflowRequest |
| AsynchronousWorkflowSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | DeleteAsynchronousWorkflowDataRequest, GetAsynchronousWorkflowByIdDataRequest, GetAsynchronousWorkflowByTypeAndReferenceIdDataRequest, SaveAsynchronousWorkflowDataRequest |
| CreditMemoOfflineService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll | ProcessCreditMemoOfflineServiceRequest |
| DataSyncStatusDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | CheckDataChangedDataRequest |
| DataSyncStatusSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetDependentTablesDataRequest, ReadChangedTablesDataRequest |
| GiftCardOfflineService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll | ProcessGiftCardOfflineServiceRequest |
| NotificationHandlerAsync | handler | Microsoft.Dynamics.Commerce.Runtime.Framework.dll |  |
| OfflineProvisioningDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll |  |
| OfflineSyncStatsSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetOfflineSyncStatsDataRequest, GetOfflinePendingTransactionCountDataRequest, GetOfflinePendingTransactionCountByShiftDataRequest |
| RequestHandlerAsyncAdapter | handler | Microsoft.Dynamics.Commerce.Runtime.dll |  |
| ServerOfflineTransactionSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | SaveOfflineTransactionsDataRequest |

## Triggers (1)

| Trigger | Assembly | Supported Requests |
|---------|----------|--------------------|
| RequestTriggerAsyncAdapter | Microsoft.Dynamics.Commerce.Runtime.dll |  |
