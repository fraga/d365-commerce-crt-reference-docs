# Inventory

## Handlers (27)

| Handler | Kind | Assembly | Supported Requests |
|---------|------|----------|--------------------|
| DeleteStockCountRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | DeleteStockCountRequest |
| GetAvailableToPromiseInventoryRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetAvailableToPromiseInventoryRequest |
| GetItemAvailableQuantitiesRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetItemAvailableQuantitiesRequest |
| GetStockCountRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetStockCountRequest |
| InventoryAdjustmentInventoryVisibilityService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.InventoryVisibilityService.dll | AdjustInventoryServiceRequest |
| InventoryAdjustmentService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll | AdjustInventoryBySalesTransactionServiceRequest |
| InventoryAvailabilityDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll |  |
| InventoryAvailabilityService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll | GetEstimatedProductWarehouseAvailabilityServiceRequest, GetEstimatedAvailabilityServiceRequest, TransformResultInventoryInformationServiceRequest, GetInventoryAvailabilityForFulfillmentStoresServiceRequest, GetInventoryAvailabilityByDimensionsServiceRequest (+6) |
| InventoryAvailabilitySqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetEstimatedProductWarehouseAvailabilityDataRequest, GetProductWarehouseInventoryUnpostedQuantityDataRequest, GetProductWarehouseInventoryLastInventoryTransactionIdDataRequest, GetProductInventoryAvailabilityForFulfillmentGroupDataRequest, GetProductDimensionsInventoryAvailabilityDataRequest (+9) |
| InventoryDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetPurchaseOrderDataRequest, GetPickingListDataRequest, GetTransferOrderDataRequest, GetWarehouseDataRequest, GetWarehouseLocationsDataRequest (+1) |
| InventoryDocumentService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll | AddInventoryInboundOutboundDocumentLineRequest, ApplyInventoryInboundOutboundDocumentMaximumQuantitiesRequest, CommitInventoryInboundOutboundDocumentOperationRequest, CreateInventoryInboundOutboundDocumentRequest, DeleteInventoryInboundOutboundDocumentLineRequest (+51) |
| InventoryDocumentSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | CreateInventoryInboundOutboundDocumentDataRequest, DeleteInventoryInboundOutboundDocumentDataRequest, DeleteInventoryInboundOutboundDocumentLineDataRequest, DeleteInventoryInboundOutboundSourceDocumentDataRequest, GetInventoryInboundOutboundDocumentDataRequest (+25) |
| InventoryDocumentTrackingDimensionService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll | AdjustInventoryDocumentSerialNumberLinesServiceRequest, GetInventoryDocumentSerialNumberLinesSummaryServiceRequest, PrepareInventoryDocumentSourceSerialNumberLineServiceRequest, ResetInventoryDocumentSerialNumberLineServiceRequest, SearchInventoryAvailableSerializedLineServiceRequest (+3) |
| InventoryDocumentTrackingDimensionSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | AdjustInventoryDocumentSerialNumberLinesDataRequest, GetInventoryDocumentSerialNumberLineDataRequest, GetInventoryDocumentSerialNumberLinesDataRequest, GetInventoryDocumentSerialNumberLinesSummaryDataRequest, GetInventoryDocumentSourceSerialNumberLinesDataRequest (+3) |
| InventoryInboundOutboundDocumentTransactionService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | CommitInventoryInboundOutboundDocumentOperationRealtimeRequest, GetInventoryInboundOutboundDocumentOperationStatusRealtimeRequest, GetInventoryInboundOutboundSourceDocumentLinesRealtimeRequest, GetInventoryInboundOutboundSourceDocumentRealtimeRequest, SearchInventoryInboundSourceDocumentsRealtimeRequest (+2) |
| InventoryLocationSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetWarehouseSiteByInventLocationIdDataRequest, GetFulfillmentGroupInventoryLocationsDataRequest |
| InventoryQuantityInventoryVisibilityService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.InventoryVisibilityService.dll | GetEstimatedQuantityServiceRequest |
| InventorySqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | SavePurchaseOrderLinesDataRequest, SavePickingListDataRequest, SaveTransferOrderDataRequest, DeletePurchaseOrderLinesDataRequest, DeletePickingListLinesDataRequest (+1) |
| InventoryVisibilityService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll | GetInventoryVisibilityParametersServiceRequest |
| InventoryVisibilitySqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetInventoryVisibilityParametersDataRequest |
| SaveStockCountRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | SaveStockCountRequest |
| StockCountDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetStockCountDataRequest |
| StockCountRealtimeService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetStockCountJournalsRealtimeRequest, GetStockCountJournalTransactionsRealtimeRequest, CommitStockCountJournalRealtimeRequest, CreateStockCountJournalRealtimeRequest, DeleteStockCountJournalRealtimeRequest |
| StockCountService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll | CreateStockCountJournalServiceRequest, SaveStockCountJournalTransactionServiceRequest, GetStockCountJournalServiceRequest, GetStockCountJournalTransactionServiceRequest, SyncStockCountJournalsFromAxServiceRequest (+4) |
| StockCountSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | DeleteStockCountJournalsDataRequest, DeleteStockCountTransactionDataRequest, CreateUpdateStockCountJournalDataRequest, CreateUpdateStockCountJournalTransactionDataRequest |
| SyncStockCountRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | SyncStockCountRequest |
| WarehouseService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll | GetWarehouseForSalesTransactionRequest |
