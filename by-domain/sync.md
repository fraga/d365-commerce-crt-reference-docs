# Sync

## Handlers (12)

| Handler | Kind | Supported Requests |
|---------|------|--------------------|
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.DataSyncStatusDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.DataSyncStatusDataService.md) | handler | [CheckDataChangedDataRequest](../by-request-type/CheckDataChangedDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.OfflineProvisioningDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.OfflineProvisioningDataService.md) | handler |  |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.OfflineSyncStatsDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.OfflineSyncStatsDataService.md) | handler | [GetOfflineSyncStatsDataRequest](../by-request-type/GetOfflineSyncStatsDataRequest.md), [GetOfflinePendingTransactionCountDataRequest](../by-request-type/GetOfflinePendingTransactionCountDataRequest.md), [GetOfflinePendingTransactionCountByShiftDataRequest](../by-request-type/GetOfflinePendingTransactionCountByShiftDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AsynchronousWorkflowSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AsynchronousWorkflowSqlServerDataService.md) | handler | [DeleteAsynchronousWorkflowDataRequest](../by-request-type/DeleteAsynchronousWorkflowDataRequest.md), [GetAsynchronousWorkflowByIdDataRequest](../by-request-type/GetAsynchronousWorkflowByIdDataRequest.md), [GetAsynchronousWorkflowByTypeAndReferenceIdDataRequest](../by-request-type/GetAsynchronousWorkflowByTypeAndReferenceIdDataRequest.md), [SaveAsynchronousWorkflowDataRequest](../by-request-type/SaveAsynchronousWorkflowDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataSyncStatusSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataSyncStatusSqlServerDataService.md) | handler | [GetDependentTablesDataRequest](../by-request-type/GetDependentTablesDataRequest.md), [ReadChangedTablesDataRequest](../by-request-type/ReadChangedTablesDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PostDataSyncOperationsService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PostDataSyncOperationsService.md) | handler | [RunPostDataSyncOperationsRequest](../by-request-type/RunPostDataSyncOperationsRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ServerOfflineTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ServerOfflineTransactionSqlServerDataService.md) | handler | [SaveOfflineTransactionsDataRequest](../by-request-type/SaveOfflineTransactionsDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Notifications.NotificationHandlerAsync (Microsoft.Dynamics.Commerce.Runtime.Framework.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Notifications.NotificationHandlerAsync.md) | handler |  |
| [Microsoft.Dynamics.Commerce.Runtime.RequestHandlerAsyncAdapter (Microsoft.Dynamics.Commerce.Runtime.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.RequestHandlerAsyncAdapter.md) | handler |  |
| [Microsoft.Dynamics.Commerce.Runtime.Services.AsynchronousWorkflowService (Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.AsynchronousWorkflowService.md) | handler | [DeleteAsynchronousWorkflowRequest](../by-request-type/DeleteAsynchronousWorkflowRequest.md), [GetAsynchronousWorkflowRequest](../by-request-type/GetAsynchronousWorkflowRequest.md), [SaveAsynchronousWorkflowRequest](../by-request-type/SaveAsynchronousWorkflowRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.CreditMemoOfflineService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.CreditMemoOfflineService.md) | handler | [ProcessCreditMemoOfflineServiceRequest](../by-request-type/ProcessCreditMemoOfflineServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.GiftCardOfflineService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.GiftCardOfflineService.md) | handler | [ProcessGiftCardOfflineServiceRequest](../by-request-type/ProcessGiftCardOfflineServiceRequest.md) |

## Triggers (1)

| Trigger | Supported Requests |
|---------|--------------------|
| Microsoft.Dynamics.Commerce.Runtime.RequestTriggerAsyncAdapter (Microsoft.Dynamics.Commerce.Runtime.dll) |  |

## Request Types (12)

### DeleteAsynchronousWorkflowDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteAsynchronousWorkflowDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AsynchronousWorkflowSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | Id |
| `long` | Version |

### DeleteAsynchronousWorkflowRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeleteAsynchronousWorkflowRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.AsynchronousWorkflowService (Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | Id |
| `long` | Version |

### GetAsynchronousWorkflowByIdDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAsynchronousWorkflowByIdDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AsynchronousWorkflowSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | Id |

### GetAsynchronousWorkflowByTypeAndReferenceIdDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAsynchronousWorkflowByTypeAndReferenceIdDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AsynchronousWorkflowSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `int` | Type |
| `string` | ReferenceId |

### GetAsynchronousWorkflowRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAsynchronousWorkflowRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.AsynchronousWorkflowService (Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | Id |
| `int` | Type |
| `string` | ReferenceId |

### ProcessCreditMemoOfflineServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProcessCreditMemoOfflineServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CreditMemoOfflineService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `decimal` | Amount |
| `RetailCreditMemoOperation` | OperationType |
| `string` | ReceiptId |
| `string` | TransactionId |
| `int` | Applied |
| `string` | EntryId |

### ProcessGiftCardOfflineServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProcessGiftCardOfflineServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.GiftCardOfflineService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `decimal` | Amount |
| `string` | CardNumber |
| `RetailGiftCardOperation` | OperationType |
| `string` | ReceiptId |
| `string` | TransactionId |

### RunPostDataSyncOperationsRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.RunPostDataSyncOperationsRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PostDataSyncOperationsService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | ChangedTables |

### SaveAsynchronousWorkflowDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveAsynchronousWorkflowDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AsynchronousWorkflowSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `AsynchronousWorkflow` | Workflow |

### SaveAsynchronousWorkflowRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveAsynchronousWorkflowRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.AsynchronousWorkflowService (Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `AsynchronousWorkflow` | Workflow |

### SaveOfflineTransactionsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveOfflineTransactionsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ServerOfflineTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `byte[]` | CompressedTransactions |

### SyncOfflineTransactionsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SyncOfflineTransactionsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.Desktop.CommerceDataExchangeService (Microsoft.Dynamics.Commerce.Runtime.Services.DataSync.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `ICollection<string>` | OfflineTransactionData |
| `int` | SqlCommandTimeout |
