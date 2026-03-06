# Inventory

## Handlers (27)

| Handler | Kind | Supported Requests |
|---------|------|--------------------|
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.InventoryDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.InventoryDataService.md) | handler | [GetPurchaseOrderDataRequest](../by-request-type/GetPurchaseOrderDataRequest.md), [GetPickingListDataRequest](../by-request-type/GetPickingListDataRequest.md), [GetTransferOrderDataRequest](../by-request-type/GetTransferOrderDataRequest.md), [GetWarehouseDataRequest](../by-request-type/GetWarehouseDataRequest.md), [GetWarehouseLocationsDataRequest](../by-request-type/GetWarehouseLocationsDataRequest.md) (+1) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.StockCountDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.StockCountDataService.md) | handler | [GetStockCountDataRequest](../by-request-type/GetStockCountDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.InventoryAvailabilityDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.InventoryAvailabilityDataService.md) | handler |  |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.Inventory.InventoryAvailabilitySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.Inventory.InventoryAvailabilitySqlServerDataService.md) | handler | [GetEstimatedProductWarehouseAvailabilityDataRequest](../by-request-type/GetEstimatedProductWarehouseAvailabilityDataRequest.md), [GetProductWarehouseInventoryUnpostedQuantityDataRequest](../by-request-type/GetProductWarehouseInventoryUnpostedQuantityDataRequest.md), [GetProductWarehouseInventoryLastInventoryTransactionIdDataRequest](../by-request-type/GetProductWarehouseInventoryLastInventoryTransactionIdDataRequest.md), [GetProductInventoryAvailabilityForFulfillmentGroupDataRequest](../by-request-type/GetProductInventoryAvailabilityForFulfillmentGroupDataRequest.md), [GetProductDimensionsInventoryAvailabilityDataRequest](../by-request-type/GetProductDimensionsInventoryAvailabilityDataRequest.md) (+9) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService.md) | handler | [CreateInventoryInboundOutboundDocumentDataRequest](../by-request-type/CreateInventoryInboundOutboundDocumentDataRequest.md), [DeleteInventoryInboundOutboundDocumentDataRequest](../by-request-type/DeleteInventoryInboundOutboundDocumentDataRequest.md), [DeleteInventoryInboundOutboundDocumentLineDataRequest](../by-request-type/DeleteInventoryInboundOutboundDocumentLineDataRequest.md), [DeleteInventoryInboundOutboundSourceDocumentDataRequest](../by-request-type/DeleteInventoryInboundOutboundSourceDocumentDataRequest.md), [GetInventoryInboundOutboundDocumentDataRequest](../by-request-type/GetInventoryInboundOutboundDocumentDataRequest.md) (+25) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentTrackingDimensionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentTrackingDimensionSqlServerDataService.md) | handler | [AdjustInventoryDocumentSerialNumberLinesDataRequest](../by-request-type/AdjustInventoryDocumentSerialNumberLinesDataRequest.md), [GetInventoryDocumentSerialNumberLineDataRequest](../by-request-type/GetInventoryDocumentSerialNumberLineDataRequest.md), [GetInventoryDocumentSerialNumberLinesDataRequest](../by-request-type/GetInventoryDocumentSerialNumberLinesDataRequest.md), [GetInventoryDocumentSerialNumberLinesSummaryDataRequest](../by-request-type/GetInventoryDocumentSerialNumberLinesSummaryDataRequest.md), [GetInventoryDocumentSourceSerialNumberLinesDataRequest](../by-request-type/GetInventoryDocumentSourceSerialNumberLinesDataRequest.md) (+3) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryLocationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryLocationSqlServerDataService.md) | handler | [GetWarehouseSiteByInventLocationIdDataRequest](../by-request-type/GetWarehouseSiteByInventLocationIdDataRequest.md), [GetFulfillmentGroupInventoryLocationsDataRequest](../by-request-type/GetFulfillmentGroupInventoryLocationsDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventorySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventorySqlServerDataService.md) | handler | [SavePurchaseOrderLinesDataRequest](../by-request-type/SavePurchaseOrderLinesDataRequest.md), [SavePickingListDataRequest](../by-request-type/SavePickingListDataRequest.md), [SaveTransferOrderDataRequest](../by-request-type/SaveTransferOrderDataRequest.md), [DeletePurchaseOrderLinesDataRequest](../by-request-type/DeletePurchaseOrderLinesDataRequest.md), [DeletePickingListLinesDataRequest](../by-request-type/DeletePickingListLinesDataRequest.md) (+1) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryVisibilitySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryVisibilitySqlServerDataService.md) | handler | [GetInventoryVisibilityParametersDataRequest](../by-request-type/GetInventoryVisibilityParametersDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.StockCountSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.StockCountSqlServerDataService.md) | handler | [DeleteStockCountJournalsDataRequest](../by-request-type/DeleteStockCountJournalsDataRequest.md), [DeleteStockCountTransactionDataRequest](../by-request-type/DeleteStockCountTransactionDataRequest.md), [CreateUpdateStockCountJournalDataRequest](../by-request-type/CreateUpdateStockCountJournalDataRequest.md), [CreateUpdateStockCountJournalTransactionDataRequest](../by-request-type/CreateUpdateStockCountJournalTransactionDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.InventoryAdjustmentInventoryVisibilityService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.InventoryVisibilityService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.InventoryAdjustmentInventoryVisibilityService.md) | handler | [AdjustInventoryServiceRequest](../by-request-type/AdjustInventoryServiceRequest.md), [UpdateProductWarehouseAvailabilityServiceRequest](../by-request-type/UpdateProductWarehouseAvailabilityServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.InventoryAdjustmentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.InventoryAdjustmentService.md) | handler | [AdjustInventoryBySalesTransactionServiceRequest](../by-request-type/AdjustInventoryBySalesTransactionServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.InventoryAvailabilityService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.InventoryAvailabilityService.md) | handler | [GetEstimatedProductWarehouseAvailabilityServiceRequest](../by-request-type/GetEstimatedProductWarehouseAvailabilityServiceRequest.md), [GetEstimatedAvailabilityServiceRequest](../by-request-type/GetEstimatedAvailabilityServiceRequest.md), [TransformResultInventoryInformationServiceRequest](../by-request-type/TransformResultInventoryInformationServiceRequest.md), [GetInventoryAvailabilityForFulfillmentStoresServiceRequest](../by-request-type/GetInventoryAvailabilityForFulfillmentStoresServiceRequest.md), [GetInventoryAvailabilityByDimensionsServiceRequest](../by-request-type/GetInventoryAvailabilityByDimensionsServiceRequest.md) (+6) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService.md) | handler | [AddInventoryInboundOutboundDocumentLineRequest](../by-request-type/AddInventoryInboundOutboundDocumentLineRequest.md), [ApplyInventoryInboundOutboundDocumentMaximumQuantitiesRequest](../by-request-type/ApplyInventoryInboundOutboundDocumentMaximumQuantitiesRequest.md), [CommitInventoryInboundOutboundDocumentOperationRequest](../by-request-type/CommitInventoryInboundOutboundDocumentOperationRequest.md), [CreateInventoryInboundOutboundDocumentRequest](../by-request-type/CreateInventoryInboundOutboundDocumentRequest.md), [DeleteInventoryInboundOutboundDocumentLineRequest](../by-request-type/DeleteInventoryInboundOutboundDocumentLineRequest.md) (+51) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentTrackingDimensionService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentTrackingDimensionService.md) | handler | [AdjustInventoryDocumentSerialNumberLinesServiceRequest](../by-request-type/AdjustInventoryDocumentSerialNumberLinesServiceRequest.md), [GetInventoryDocumentSerialNumberLinesSummaryServiceRequest](../by-request-type/GetInventoryDocumentSerialNumberLinesSummaryServiceRequest.md), [PrepareInventoryDocumentSourceSerialNumberLineServiceRequest](../by-request-type/PrepareInventoryDocumentSourceSerialNumberLineServiceRequest.md), [ResetInventoryDocumentSerialNumberLineServiceRequest](../by-request-type/ResetInventoryDocumentSerialNumberLineServiceRequest.md), [SearchInventoryAvailableSerializedLineServiceRequest](../by-request-type/SearchInventoryAvailableSerializedLineServiceRequest.md) (+3) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.InventoryInboundOutboundDocumentTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.InventoryInboundOutboundDocumentTransactionService.md) | handler | [CommitInventoryInboundOutboundDocumentOperationRealtimeRequest](../by-request-type/CommitInventoryInboundOutboundDocumentOperationRealtimeRequest.md), [GetInventoryInboundOutboundDocumentOperationStatusRealtimeRequest](../by-request-type/GetInventoryInboundOutboundDocumentOperationStatusRealtimeRequest.md), [GetInventoryInboundOutboundSourceDocumentLinesRealtimeRequest](../by-request-type/GetInventoryInboundOutboundSourceDocumentLinesRealtimeRequest.md), [GetInventoryInboundOutboundSourceDocumentRealtimeRequest](../by-request-type/GetInventoryInboundOutboundSourceDocumentRealtimeRequest.md), [SearchInventoryInboundSourceDocumentsRealtimeRequest](../by-request-type/SearchInventoryInboundSourceDocumentsRealtimeRequest.md) (+2) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.InventoryQuantityInventoryVisibilityService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.InventoryVisibilityService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.InventoryQuantityInventoryVisibilityService.md) | handler | [GetEstimatedQuantityServiceRequest](../by-request-type/GetEstimatedQuantityServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.InventoryVisibilityService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.InventoryVisibilityService.md) | handler | [GetInventoryVisibilityParametersServiceRequest](../by-request-type/GetInventoryVisibilityParametersServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.StockCountRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.StockCountRealtimeService.md) | handler | [GetStockCountJournalsRealtimeRequest](../by-request-type/GetStockCountJournalsRealtimeRequest.md), [GetStockCountJournalTransactionsRealtimeRequest](../by-request-type/GetStockCountJournalTransactionsRealtimeRequest.md), [CommitStockCountJournalRealtimeRequest](../by-request-type/CommitStockCountJournalRealtimeRequest.md), [CreateStockCountJournalRealtimeRequest](../by-request-type/CreateStockCountJournalRealtimeRequest.md), [DeleteStockCountJournalRealtimeRequest](../by-request-type/DeleteStockCountJournalRealtimeRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.StockCountService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.StockCountService.md) | handler | [CreateStockCountJournalServiceRequest](../by-request-type/CreateStockCountJournalServiceRequest.md), [SaveStockCountJournalTransactionServiceRequest](../by-request-type/SaveStockCountJournalTransactionServiceRequest.md), [GetStockCountJournalServiceRequest](../by-request-type/GetStockCountJournalServiceRequest.md), [GetStockCountJournalTransactionServiceRequest](../by-request-type/GetStockCountJournalTransactionServiceRequest.md), [SyncStockCountJournalsFromAxServiceRequest](../by-request-type/SyncStockCountJournalsFromAxServiceRequest.md) (+4) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.WarehouseService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.WarehouseService.md) | handler | [GetWarehouseForSalesTransactionRequest](../by-request-type/GetWarehouseForSalesTransactionRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.ChannelProductAvailability.GetAvailableToPromiseInventoryRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.ChannelProductAvailability.GetAvailableToPromiseInventoryRequestHandler.md) | single_handler | [GetAvailableToPromiseInventoryRequest](../by-request-type/GetAvailableToPromiseInventoryRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.DeleteStockCountRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.DeleteStockCountRequestHandler.md) | single_handler | [DeleteStockCountRequest](../by-request-type/DeleteStockCountRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetItemAvailableQuantitiesRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetItemAvailableQuantitiesRequestHandler.md) | single_handler | [GetItemAvailableQuantitiesRequest](../by-request-type/GetItemAvailableQuantitiesRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStockCountRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStockCountRequestHandler.md) | single_handler | [GetStockCountRequest](../by-request-type/GetStockCountRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveStockCountRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveStockCountRequestHandler.md) | single_handler | [SaveStockCountRequest](../by-request-type/SaveStockCountRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.SyncStockCountRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.SyncStockCountRequestHandler.md) | single_handler | [SyncStockCountRequest](../by-request-type/SyncStockCountRequest.md) |

## Request Types (135)

### AddInventoryInboundOutboundDocumentLineRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AddInventoryInboundOutboundDocumentLineRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `InventoryInboundOutboundDocumentLine` | Line |

### AdjustInventoryDocumentSerialNumberLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AdjustInventoryDocumentSerialNumberLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentTrackingDimensionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | WorkDocumentId |
| `ICollection<string>` | DocumentLineIds |
| `ICollection<InventoryDocumentSerialNumberLine>` | Lines |

### AdjustInventoryDocumentSerialNumberLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AdjustInventoryDocumentSerialNumberLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentTrackingDimensionService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `InventoryInboundOutboundDocument` | Document |
| `ICollection<InventoryInboundOutboundDocumentLine>` | DocumentLines |

### AdjustInventoryServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AdjustInventoryServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryAdjustmentInventoryVisibilityService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.InventoryVisibilityService.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ICollection<InventoryAdjustment>` | InventoryAdjustments |

### ApplyInventoryInboundOutboundDocumentMaximumQuantitiesRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ApplyInventoryInboundOutboundDocumentMaximumQuantitiesRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `string` | Location |

### CommitInventoryInboundOutboundDocumentOperationRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.CommitInventoryInboundOutboundDocumentOperationRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryInboundOutboundDocumentTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `InventoryInboundOutboundCommitDocument` | Document |

### CommitInventoryInboundOutboundDocumentOperationRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CommitInventoryInboundOutboundDocumentOperationRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `long?` | DocumentVersion |

### CommitStockCountJournalRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.CommitStockCountJournalRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StockCountRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `StockCountJournal` | Journal |

### CommitStockCountTransactionsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CommitStockCountTransactionsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StockCountService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | JournalId |
| `IEnumerable<StockCountJournalTransaction>` | StockCountJournalTransactions |

### CreateInventoryInboundOutboundDocumentDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateInventoryInboundOutboundDocumentDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `InventoryInboundOutboundDocument` | Document |

### CreateInventoryInboundOutboundDocumentRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateInventoryInboundOutboundDocumentRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `InventoryInboundOutboundDocument` | Document |

### CreateStockCountJournalRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.CreateStockCountJournalRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StockCountRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | LocationId |
| `string` | Description |
| `string` | UserId |

### CreateStockCountJournalServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateStockCountJournalServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StockCountService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | Description |
| `string` | UserId |

### CreateUpdateStockCountJournalDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateUpdateStockCountJournalDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.StockCountSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<StockCountJournal>` | Journals |

### CreateUpdateStockCountJournalTransactionDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateUpdateStockCountJournalTransactionDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.StockCountSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<StockCountJournalTransaction>` | JournalTransactions |

### DeleteInventoryDocumentSerialNumberLinesBySourceDocumentDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteInventoryDocumentSerialNumberLinesBySourceDocumentDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentTrackingDimensionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | SourceDocumentRecordId |
| `InventorySourceDocumentType` | SourceDocumentType |

### DeleteInventoryDocumentSourceDocumentLineCommitRecordsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteInventoryDocumentSourceDocumentLineCommitRecordsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | SourceDocumentRecordId |
| `InventorySourceDocumentType` | SourceDocumentType |

### DeleteInventoryInboundOutboundDocumentDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteInventoryInboundOutboundDocumentDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `long?` | DocumentVersion |

### DeleteInventoryInboundOutboundDocumentLineDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteInventoryInboundOutboundDocumentLineDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `string` | LineId |
| `long?` | LineVersion |

### DeleteInventoryInboundOutboundDocumentLineRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeleteInventoryInboundOutboundDocumentLineRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `string` | LineId |
| `long?` | LineVersion |

### DeleteInventoryInboundOutboundDocumentRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeleteInventoryInboundOutboundDocumentRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `long?` | DocumentVersion |

### DeleteInventoryInboundOutboundSourceDocumentDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteInventoryInboundOutboundSourceDocumentDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | RecordId |
| `InventorySourceDocumentType` | DocumentType |

### DeleteStockCountJournalRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.DeleteStockCountJournalRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StockCountRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | JournalId |

### DeleteStockCountJournalServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeleteStockCountJournalServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StockCountService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | JournalId |

### DeleteStockCountJournalsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteStockCountJournalsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.StockCountSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | JournalIds |

### DeleteStockCountRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.DeleteStockCountRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.DeleteStockCountRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | JournalId |
| `long` | StockCountLineId |
| `long` | ProductRecordId |
| `string` | ItemId |
| `string` | InventSizeId |
| `string` | InventColorId |
| `string` | InventStyleId |
| `string` | ConfigId |
| `bool` | IsCascadeJournalDelete |

### DeleteStockCountTransactionDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteStockCountTransactionDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.StockCountSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | JournalId |
| `long` | StockCountLineId |
| `long` | ProductRecordId |
| `string` | ItemId |
| `string` | InventSizeId |
| `string` | InventColorId |
| `string` | InventStyleId |
| `string` | ConfigId |

### DeleteStockCountTransactionServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeleteStockCountTransactionServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StockCountService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | JournalId |
| `long` | StockCountLineId |
| `long` | ProductRecordId |
| `string` | ItemId |
| `string` | InventSizeId |
| `string` | InventColorId |
| `string` | InventStyleId |
| `string` | ConfigId |

### GetAvailableToPromiseInventoryRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.Inventory.GetAvailableToPromiseInventoryRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.AvailabilityTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `long` | ProductId |
| `string` | StoreId |
| `string` | ItemId |

### GetAvailableToPromiseInventoryRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetAvailableToPromiseInventoryRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.ChannelProductAvailability.GetAvailableToPromiseInventoryRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `long` | ProductId |
| `string` | StoreId |
| `string` | ItemId |

### GetEstimatedOnHandQuantityForInventoryDimensionsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEstimatedOnHandQuantityForInventoryDimensionsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.Inventory.InventoryAvailabilitySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ICollection<ItemEstimatedOnHandQuantitySearchCriteria>` | SearchCriteria |

### GetEstimatedProductWarehouseAvailabilityDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEstimatedProductWarehouseAvailabilityDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.Inventory.InventoryAvailabilitySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<ProductWarehouse>` | ProductWarehouses |

### GetEstimatedProductWarehouseAvailabilityServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEstimatedProductWarehouseAvailabilityServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryAvailabilityService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<ProductWarehouse>` | ProductWarehouses |
| `QuantityUnitType` | QuantityUnitType |

### GetInventoryAvailabilityByDimensionsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetInventoryAvailabilityByDimensionsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryAvailabilityService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | InventLocationId |
| `long` | MasterProductId |
| `IEnumerable<ProductDimensionCombination>` | ProductDimensionCombinations |

### GetInventoryDimensionsIncrementalUnpostedQuantityDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryDimensionsIncrementalUnpostedQuantityDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.Inventory.InventoryAvailabilitySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ICollection<InventoryDimensionsUnpostedQuantity>` | UnpostedQuantities |

### GetInventoryDimensionsUnpostedQuantityDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryDimensionsUnpostedQuantityDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.Inventory.InventoryAvailabilitySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ICollection<InventoryDimensionsUnpostedQuantity>` | UnpostedQuantities |

### GetInventoryDocumentLinesByIdsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryDocumentLinesByIdsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ICollection<string>` | DocumentLineIds |
| `bool` | IncludeSourceDocumentLines |
| `bool` | ShouldMergeWorkAndSourceDocumentLines |

### GetInventoryDocumentSerialNumberLineDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryDocumentSerialNumberLineDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentTrackingDimensionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `string` | DocumentLineId |
| `string` | SerialNumberLineId |

### GetInventoryDocumentSerialNumberLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryDocumentSerialNumberLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentTrackingDimensionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `ICollection<string>` | DocumentLineIds |

### GetInventoryDocumentSerialNumberLinesSummaryDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryDocumentSerialNumberLinesSummaryDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentTrackingDimensionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `string` | DocumentLineId |

### GetInventoryDocumentSerialNumberLinesSummaryServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetInventoryDocumentSerialNumberLinesSummaryServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentTrackingDimensionService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `string` | DocumentLineId |

### GetInventoryDocumentSourceSerialNumberLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryDocumentSourceSerialNumberLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentTrackingDimensionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `InventorySourceDocumentType` | SourceDocumentType |
| `string` | SourceDocumentId |
| `ICollection<long>` | DocumentLineRecordIds |

### GetInventoryDocumentValidationResultLinesByDocumentIdAndCategoryNameDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryDocumentValidationResultLinesByDocumentIdAndCategoryNameDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `long` | DocumentVersion |
| `InventoryDocumentValidationResultSeverity` | MinimumSeverity |
| `string` | CategoryName |

### GetInventoryInboundOutboundDocumentDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryInboundOutboundDocumentDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |

### GetInventoryInboundOutboundDocumentLineDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryInboundOutboundDocumentLineDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `string` | LineId |

### GetInventoryInboundOutboundDocumentLineServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetInventoryInboundOutboundDocumentLineServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `string` | LineId |
| `bool` | IsSourceLineRequired |

### GetInventoryInboundOutboundDocumentLinesBySourceDocumentDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryInboundOutboundDocumentLinesBySourceDocumentDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | RecordId |
| `InventorySourceDocumentType` | DocumentType |
| `string` | Receiver |
| `long?` | ProductId |
| `ICollection<long>` | ProductIds |
| `string` | DocumentId |
| `string` | LocationId |
| `string` | ToLocationId |
| `InventoryJournalPosAdjustmentType?` | AdjustmentType |
| `string` | StaffId |
| `bool` | AllowInboundTransferOrderEmptyWorkline |

### GetInventoryInboundOutboundDocumentLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryInboundOutboundDocumentLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `long?` | ProductId |
| `string` | LocationId |
| `ICollection<long>` | ProductIds |
| `string` | ToLocationId |
| `InventoryJournalPosAdjustmentType?` | AdjustmentTypeValue |

### GetInventoryInboundOutboundDocumentLinesSummaryDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryInboundOutboundDocumentLinesSummaryDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |

### GetInventoryInboundOutboundDocumentLinesSummaryServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetInventoryInboundOutboundDocumentLinesSummaryServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |

### GetInventoryInboundOutboundDocumentOperationStatusRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetInventoryInboundOutboundDocumentOperationStatusRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryInboundOutboundDocumentTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `Guid` | RequestId |

### GetInventoryInboundOutboundDocumentRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetInventoryInboundOutboundDocumentRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `bool` | IsSourceDocumentRequired |

### GetInventoryInboundOutboundDocumentsBySourceDocumentsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryInboundOutboundDocumentsBySourceDocumentsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<InventoryInboundOutboundSourceDocument>` | SourceDocuments |

### GetInventoryInboundOutboundDocumentsBySourceDocumentsRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetInventoryInboundOutboundDocumentsBySourceDocumentsRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<InventoryInboundOutboundSourceDocument>` | Documents |

### GetInventoryInboundOutboundSourceDocumentByIdDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryInboundOutboundSourceDocumentByIdDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `InventorySourceDocumentType` | DocumentType |

### GetInventoryInboundOutboundSourceDocumentDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryInboundOutboundSourceDocumentDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | RecordId |
| `InventorySourceDocumentType` | DocumentType |

### GetInventoryInboundOutboundSourceDocumentLineDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryInboundOutboundSourceDocumentLineDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | SourceDocumentRecordId |
| `InventorySourceDocumentType` | SourceDocumentType |
| `long` | SourceDocumentLineRecordId |

### GetInventoryInboundOutboundSourceDocumentLinesRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetInventoryInboundOutboundSourceDocumentLinesRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryInboundOutboundDocumentTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `InventorySourceDocumentType` | DocumentType |

### GetInventoryInboundOutboundSourceDocumentRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetInventoryInboundOutboundSourceDocumentRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryInboundOutboundDocumentTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `InventorySourceDocumentType` | DocumentType |

### GetInventoryInboundOutboundWorkToSourceDocumentMapDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryInboundOutboundWorkToSourceDocumentMapDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |

### GetInventoryJournalNameByIdsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryJournalNameByIdsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | JournalNameIds |

### GetInventoryJournalNameByJournalTypesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryJournalNameByJournalTypesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<ExtensibleInventoryJournalType>` | JournalTypes |

### GetInventoryLevelProfilesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetInventoryLevelProfilesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.Inventory.InventoryAvailabilitySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ICollection<string>` | ProfileIds |

### GetItemAvailabilitiesByItemQuantitiesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemQuantitiesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ProductAvailabilityService (Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<ItemQuantity>` | ItemQuantities |
| `string` | CustomerAccountNumber |
| `int` | MaxWarehousesPerItem |

### GetItemAvailabilitiesByItemWarehousesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemWarehousesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ProductAvailabilityService (Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<ItemWarehouse>` | ItemWarehouses |

### GetItemAvailabilitiesByItemsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ProductAvailabilityService (Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<ItemVariantInventoryDimension>` | Items |
| `string` | CustomerAccountNumber |

### GetItemAvailabilitiesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemAvailabilitiesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ProductAvailabilitySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ItemAvailabilitiesQueryCriteria` | QueryCriteria |

### GetItemAvailableQuantitiesByItemsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailableQuantitiesByItemsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ProductAvailabilityService (Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<ItemVariantInventoryDimension>` | Items |
| `string` | CustomerAccountNumber |

### GetItemAvailableQuantitiesRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailableQuantitiesRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetItemAvailableQuantitiesRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `IEnumerable<ItemUnit>` | ItemUnits |
| `string` | CustomerAccountNumber |

### GetItemInventoryUnitsOfMeasureDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemInventoryUnitsOfMeasureDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.UnitOfMeasureSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | ItemId |

### GetProductDimensionsInventoryAvailabilityDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductDimensionsInventoryAvailabilityDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.Inventory.InventoryAvailabilitySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<ProductWarehouse>` | ProductWarehouses |

### GetProductInventoryLevelProfileMappingsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductInventoryLevelProfileMappingsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.Inventory.InventoryAvailabilitySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ICollection<long>` | ProductIds |

### GetProductWarehouseIncrementalInventoryUnpostedQuantityDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductWarehouseIncrementalInventoryUnpostedQuantityDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.Inventory.InventoryAvailabilitySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<ProductWarehouseInventoryUnpostedQuantity>` | UnpostedQuantities |
| `UnpostedQuantitySearchCriteria` | SearchCriteria |

### GetProductWarehouseInventoryUnpostedQuantityDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductWarehouseInventoryUnpostedQuantityDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.Inventory.InventoryAvailabilitySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<ProductWarehouseInventoryUnpostedQuantity>` | UnpostedQuantities |
| `UnpostedQuantitySearchCriteria` | SearchCriteria |

### GetProductWarehouseInventoryUnpostedQuantityServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductWarehouseInventoryUnpostedQuantityServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryAvailabilityService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ICollection<ProductWarehouse>` | ProductWarehouses |

### GetStockCountDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetStockCountDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.StockCountDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | JournalId |
| `bool` | TransactionRecordsOnly |

### GetStockCountJournalServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StockCountService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | JournalId |

### GetStockCountJournalTransactionServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalTransactionServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StockCountService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | JournalId |

### GetStockCountJournalTransactionsRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetStockCountJournalTransactionsRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StockCountRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | JournalId |
| `string` | LocationId |

### GetStockCountJournalsRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetStockCountJournalsRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StockCountRealtimeService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | LocationId |

### GetStockCountRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetStockCountRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetStockCountRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | JournalId |
| `bool` | IncludeOnlyTransactions |

### GetWarehouseAddressIndiaDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetWarehouseAddressIndiaDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.IndiaTaxSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | WarehouseId |

### GetWarehouseDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetWarehouseDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.InventoryDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | WarehouseId |

### GetWarehouseDetailsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetWarehouseDetailsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ShippingDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | WarehouseIds |

### GetWarehouseLocationsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetWarehouseLocationsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.InventoryDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | WarehouseId |
| `string` | SearchText |
| `WarehouseLocationSearchCriteria` | SearchCriteria |

### GetWarehouseSiteByInventLocationIdDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetWarehouseSiteByInventLocationIdDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryLocationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ReadOnlyCollection<string>` | InventoryLocationIds |
| `string` | DataAreaId |

### PauseInventoryInboundOutboundDocumentRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PauseInventoryInboundOutboundDocumentRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `long?` | DocumentVersion |

### PrepareInventoryDocumentSourceSerialNumberLineServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PrepareInventoryDocumentSourceSerialNumberLineServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentTrackingDimensionService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `InventoryInboundOutboundSourceDocument` | Document |
| `ICollection<InventoryInboundOutboundSourceDocumentLine>` | Lines |

### PrepareInventoryInboundOutboundSourceDocumentRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PrepareInventoryInboundOutboundSourceDocumentRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `InventorySourceDocumentType` | DocumentType |
| `bool` | ForceRefresh |

### RefreshInventoryInboundOutboundDocumentOperationStatusRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.RefreshInventoryInboundOutboundDocumentOperationStatusRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |

### ResetInventoryDocumentSerialNumberLineServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ResetInventoryDocumentSerialNumberLineServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentTrackingDimensionService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | WorkDocumentId |
| `InventoryDocumentSerialNumberLineResetAction` | ResetAction |

### ResumeInventoryInboundOutboundDocumentRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ResumeInventoryInboundOutboundDocumentRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `long?` | DocumentVersion |

### SaveInventoryDocumentCommitRecordsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveInventoryDocumentCommitRecordsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `InventoryInboundOutboundCommitDocument` | CommitDocument |

### SaveInventoryDocumentSourceDocumentLineCommitRecordsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveInventoryDocumentSourceDocumentLineCommitRecordsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<InventoryDocumentSourceDocumentLineCommitRecord>` | CommitRecords |

### SaveInventoryDocumentValidationResultLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveInventoryDocumentValidationResultLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<InventoryDocumentValidationResultLine>` | Lines |

### SaveInventoryInboundOutboundDocumentDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveInventoryInboundOutboundDocumentDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `InventoryInboundOutboundDocument` | Document |

### SaveInventoryInboundOutboundDocumentLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveInventoryInboundOutboundDocumentLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<InventoryInboundOutboundDocumentLine>` | Lines |

### SaveInventoryInboundOutboundDocumentLinesRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveInventoryInboundOutboundDocumentLinesRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<InventoryInboundOutboundDocumentLine>` | Lines |

### SaveInventoryInboundOutboundDocumentRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveInventoryInboundOutboundDocumentRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `InventoryInboundOutboundDocument` | Document |

### SaveInventoryInboundOutboundSourceDocumentDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveInventoryInboundOutboundSourceDocumentDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `InventoryInboundOutboundSourceDocument` | Document |
| `IEnumerable<InventoryInboundOutboundSourceDocumentLine>` | DocumentLines |
| `ICollection<InventoryDocumentSourceSerialNumberLine>` | SourceSerialNumberLines |

### SaveStockCountJournalTransactionServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveStockCountJournalTransactionServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StockCountService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | JournalId |
| `IEnumerable<StockCountJournalTransaction>` | StockCountJournalTransactions |

### SaveStockCountRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStockCountRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveStockCountRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | JournalId |
| `ReadOnlyCollection<StockCountJournalTransaction>` | StockCountJournalTransactionList |
| `bool` | IsCommitted |

### SearchInventoryAvailableSerializedLineServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SearchInventoryAvailableSerializedLineServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentTrackingDimensionService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |

### SearchInventoryDocumentLinesRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SearchInventoryDocumentLinesRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `InventoryDocumentLineSearchCriteria` | SearchCriteria |
| `bool` | IncludeSerialNumberLines |

### SearchInventoryDocumentSerialNumberLinesBySourceDocumentDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchInventoryDocumentSerialNumberLinesBySourceDocumentDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentTrackingDimensionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | SourceDocumentRecordId |
| `InventorySourceDocumentType` | SourceDocumentType |
| `long` | SourceDocumentLineRecordId |

### SearchInventoryDocumentSerialNumberLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SearchInventoryDocumentSerialNumberLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentTrackingDimensionService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | WorkDocumentId |
| `InventoryDocumentSerialNumberLineSearchCriteria` | SearchCriteria |

### SearchInventoryDocumentSourceDocumentLineCommitRecordsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchInventoryDocumentSourceDocumentLineCommitRecordsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | SourceDocumentRecordId |
| `InventorySourceDocumentType` | SourceDocumentType |
| `long` | SourceDocumentLineRecordId |

### SearchInventoryDocumentValidationResultLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SearchInventoryDocumentValidationResultLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `InventoryDocumentValidationResultSearchCriteria` | SearchCriteria |

### SearchInventoryInboundOutboundDocumentsByOperationTypesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchInventoryInboundOutboundDocumentsByOperationTypesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | Sender |
| `string` | Receiver |
| `IEnumerable<InventoryInboundOutboundDocumentOperationType>` | OperationTypes |
| `InventoryDocumentSearchCriteria` | SearchCriteria |

### SearchInventoryInboundOutboundDocumentsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchInventoryInboundOutboundDocumentsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | Sender |
| `string` | Receiver |
| `InventoryInboundOutboundDocumentOperationType` | OperationType |
| `InventoryDocumentSearchCriteria` | SearchCriteria |

### SearchInventoryInboundSourceDocumentsRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.SearchInventoryInboundSourceDocumentsRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryInboundOutboundDocumentTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `InventoryDocumentSearchCriteria` | SearchCriteria |

### SearchInventoryJournalNamesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SearchInventoryJournalNamesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `InventoryJournalNameSearchCriteria` | SearchCriteria |

### SearchInventoryOutboundSourceDocumentsRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.SearchInventoryOutboundSourceDocumentsRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryInboundOutboundDocumentTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `InventoryDocumentSearchCriteria` | SearchCriteria |

### SearchWarehousesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchWarehousesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.InventoryDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | SearchText |
| `DeliveryModeTypeFilter` | DeliveryModeTypeFilter |

### StartWorkingOnInventoryInboundOutboundDocumentRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.StartWorkingOnInventoryInboundOutboundDocumentRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | SourceDocumentId |
| `InventorySourceDocumentType` | SourceDocumentType |

### SyncInventorySourceDocumentServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SyncInventorySourceDocumentServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | InventorySourceDocumentId |
| `InventorySourceDocumentType` | SourceDocumentType |

### SyncStockCountRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.SyncStockCountRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.SyncStockCountRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | JournalId |

### SyncStockCountTransactionsFromAxServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SyncStockCountTransactionsFromAxServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.StockCountService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | JournalId |

### TransformResultInventoryInformationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.TransformResultInventoryInformationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryAvailabilityService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ProductWarehouseInventoryInformation` | InventoryInformation |

### UpdateInventoryDocumentSerialNumberLineRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateInventoryDocumentSerialNumberLineRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentTrackingDimensionService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | WorkDocumentId |
| `InventoryDocumentSerialNumberLineUpdateAction` | UpdateAction |

### UpdateInventoryDocumentSerialNumberLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UpdateInventoryDocumentSerialNumberLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryDocumentTrackingDimensionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ICollection<InventoryDocumentSerialNumberLine>` | Lines |

### UpdateInventoryInboundOutboundDocumentLineRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateInventoryInboundOutboundDocumentLineRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `InventoryInboundOutboundDocumentLine` | Line |

### UpdateInventoryInboundOutboundDocumentLinesByCriteriaRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateInventoryInboundOutboundDocumentLinesByCriteriaRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `InventoryDocumentLineFilterCriteria` | FilterCriteria |
| `InventoryDocumentUpdateLinesAction` | UpdateAction |
| `InventoryDocumentLineOperationResultSettings` | ReturnUpdatedLinesPolicy |

### UpdateInventoryInboundOutboundDocumentLinesByProductRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateInventoryInboundOutboundDocumentLinesByProductRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `long` | ProductId |
| `decimal` | Quantity |
| `string` | LocationId |

### UpdateInventoryInboundOutboundDocumentLinesRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateInventoryInboundOutboundDocumentLinesRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `IEnumerable<InventoryInboundOutboundDocumentLine>` | Lines |
| `InventoryInboundOutboundDocumentUpdateLinesSourceType` | SourceType |

### UpdateInventoryInboundOutboundDocumentNoteRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateInventoryInboundOutboundDocumentNoteRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `string` | Note |
| `long?` | DocumentVersion |

### UpdateInventoryInboundOutboundDocumentRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateInventoryInboundOutboundDocumentRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `InventoryInboundOutboundDocument` | Document |

### UpdateInventoryInboundOutboundDocumentStatusRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateInventoryInboundOutboundDocumentStatusRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `InventoryDocumentStatus` | Status |
| `long?` | DocumentVersion |

### UpdateInventoryInboundOutboundDocumentWorkingTerminalRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateInventoryInboundOutboundDocumentWorkingTerminalRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `long?` | DocumentVersion |

### UpdateProductWarehouseAvailabilityServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateProductWarehouseAvailabilityServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryAdjustmentInventoryVisibilityService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.InventoryVisibilityService.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<ProductWarehouseQuantity>` | ProductWarehouseQuantities |

### ValidateInventoryDocumentSerialNumberLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateInventoryDocumentSerialNumberLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentTrackingDimensionService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ICollection<InventoryInboundOutboundDocumentLine>` | Lines |

### ValidateInventoryDocumentServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateInventoryDocumentServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `long?` | DocumentVersion |

### ValidateInventoryInboundOutboundDocumentLinesUpdateRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateInventoryInboundOutboundDocumentLinesUpdateRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<InventoryInboundOutboundDocumentLine>` | Lines |
| `InventoryInboundOutboundDocumentOperationType` | OperationType |
| `InventoryInboundOutboundDocumentUpdateLinesSourceType` | SourceType |
| `InventoryInboundOutboundDocument` | Document |

### ValidateUpdateInventoryInboundOutboundDocumentLineRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateUpdateInventoryInboundOutboundDocumentLineRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `InventoryInboundOutboundDocumentLine` | Line |

### ValidateUpdateInventoryInboundOutboundDocumentRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateUpdateInventoryInboundOutboundDocumentRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `InventoryInboundOutboundDocument` | InventoryDocument |
