# Order

## Handlers (70)

| Handler | Kind | Supported Requests |
|---------|------|--------------------|
| [Microsoft.Dynamics.Commerce.Runtime.Data.Services.SqlServer.RemoteSalesOrderCacheDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Data.Services.SqlServer.RemoteSalesOrderCacheDataService.md) | handler | [AddOrUpdateRemoteSalesOrderCacheDataRequest](../by-request-type/AddOrUpdateRemoteSalesOrderCacheDataRequest.md), [GetRemoteSalesOrderCacheDataRequest](../by-request-type/GetRemoteSalesOrderCacheDataRequest.md), [RemoveRemoteSalesOrderCacheDataRequest](../by-request-type/RemoveRemoteSalesOrderCacheDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Data.Services.SqlServer.SalesOrderSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Data.Services.SqlServer.SalesOrderSqlServerDataService.md) | handler | [SearchSalesOrdersHeaderDataRequest](../by-request-type/SearchSalesOrdersHeaderDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.FulfillmentGroupDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.FulfillmentGroupDataService.md) | handler | [GetFulfillmentGroupMembersDataRequest](../by-request-type/GetFulfillmentGroupMembersDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.SalesOrderDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.SalesOrderDataService.md) | handler | [GetSalesOrderDetailsDataRequest](../by-request-type/GetSalesOrderDetailsDataRequest.md), [GetSalesOrderByChannelReferenceLookupCriteriaDataRequest](../by-request-type/GetSalesOrderByChannelReferenceLookupCriteriaDataRequest.md), [GetCustomerOrderParametersDataRequest](../by-request-type/GetCustomerOrderParametersDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.SalesTransactionDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.SalesTransactionDataService.md) | handler | [SaveSalesTransactionDataRequest](../by-request-type/SaveSalesTransactionDataRequest.md), [SearchSalesTransactionDataRequest](../by-request-type/SearchSalesTransactionDataRequest.md), [GetReceiptMaskDataRequest](../by-request-type/GetReceiptMaskDataRequest.md), [GetReceiptMasksDataRequest](../by-request-type/GetReceiptMasksDataRequest.md), [GetTenderLinesForSalesOrderDataRequest](../by-request-type/GetTenderLinesForSalesOrderDataRequest.md) (+12) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.NonSalesTransactionDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.NonSalesTransactionDataService.md) | handler | [GetTransactionTenderTypeDataRequest](../by-request-type/GetTransactionTenderTypeDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SalesTransactionDataSharedService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SalesTransactionDataSharedService.md) | handler | [GetReturnQuantitiesAfterLastReturnProcessedTimeDataRequest](../by-request-type/GetReturnQuantitiesAfterLastReturnProcessedTimeDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.Inventory.FulfillmentLineStatusSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.Inventory.FulfillmentLineStatusSqlServerDataService.md) | handler | [GetLatestFulfillmentLineTransactionsDataRequest](../by-request-type/GetLatestFulfillmentLineTransactionsDataRequest.md), [InsertFulfillmentLineTransactionsDataRequest](../by-request-type/InsertFulfillmentLineTransactionsDataRequest.md), [GetSalesLineReferenceLookupsDataRequest](../by-request-type/GetSalesLineReferenceLookupsDataRequest.md), [InsertSalesLineReferenceLookupsDataRequest](../by-request-type/InsertSalesLineReferenceLookupsDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.NonSalesTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.NonSalesTransactionSqlServerDataService.md) | handler | [SaveNonSalesTransactionDataRequest](../by-request-type/SaveNonSalesTransactionDataRequest.md), [GetCurrentShiftNonSalesTransactionsDataRequest](../by-request-type/GetCurrentShiftNonSalesTransactionsDataRequest.md), [GetStoreSafeDataRequest](../by-request-type/GetStoreSafeDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ReceiptSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ReceiptSqlServerDataService.md) | handler | [GetEmailReceiptSettingsDataRequest](../by-request-type/GetEmailReceiptSettingsDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.SalesTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.SalesTransactionSqlServerDataService.md) | handler | [GetCartsDataRequest](../by-request-type/GetCartsDataRequest.md), [SaveCartVersionedDataRequest](../by-request-type/SaveCartVersionedDataRequest.md), [SaveCartDataRequest](../by-request-type/SaveCartDataRequest.md), [InsertTransactionHeaderDataRequest](../by-request-type/InsertTransactionHeaderDataRequest.md), [InsertSalesTransactionTablesDataRequest](../by-request-type/InsertSalesTransactionTablesDataRequest.md) (+10) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.WarrantySalesTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.WarrantySalesTransactionSqlServerDataService.md) | handler | [GetWarrantyTransactionsDataRequest](../by-request-type/GetWarrantyTransactionsDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.SalesTransactionSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.SalesTransactionSqlSharedDataService.md) | handler | [DeleteCartDataRequest](../by-request-type/DeleteCartDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DocumentProvider.SequentialSignature.SequentialSignatureSalesOrderAdjustmentService (Microsoft.Dynamics.Commerce.Runtime.DocumentProvider.SequentialSignature.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DocumentProvider.SequentialSignature.SequentialSignatureSalesOrderAdjustmentService.md) | handler | [SequentialSignatureSalesOrderAdjustmentRequest](../by-request-type/SequentialSignatureSalesOrderAdjustmentRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentReceiptService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentReceiptService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md), [GetCustomReceiptsRequest](../by-request-type/GetCustomReceiptsRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.GteReceiptService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.GteReceiptService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md), [PopulateTaxSummaryIndiaServiceRequest](../by-request-type/PopulateTaxSummaryIndiaServiceRequest.md), [GetFormattedNumberServiceRequest](../by-request-type/GetFormattedNumberServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.France.ReceiptsContentDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.France.ReceiptsContentDataService.md) | handler | [InsertReceiptsContentDataRequest](../by-request-type/InsertReceiptsContentDataRequest.md), [GetReceiptsContentDataRequest](../by-request-type/GetReceiptsContentDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.SaudiArabia.SalesTransactionAdjustmentsDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.SaudiArabia.SalesTransactionAdjustmentsDataService.md) | handler | [InsertSalesTransAdjustmentsDataRequest](../by-request-type/InsertSalesTransAdjustmentsDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Austria.Receipts.ReceiptAustriaService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Austria.Receipts.ReceiptAustriaService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Czechia.Receipts.ReceiptCzechiaService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Czechia.Receipts.ReceiptCzechiaService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.France.Receipts.ReceiptFranceService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.France.Receipts.ReceiptFranceService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Germany.Receipts.ReceiptGermanyService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Germany.Receipts.ReceiptGermanyService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.Receipt.GteReceiptService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.Receipt.GteReceiptService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md), [PopulateTaxSummaryIndiaServiceRequest](../by-request-type/PopulateTaxSummaryIndiaServiceRequest.md), [GetFormattedNumberServiceRequest](../by-request-type/GetFormattedNumberServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.TaxRegistrationId.Services.TaxRegistrationIdReceiptService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.TaxRegistrationId.Services.TaxRegistrationIdReceiptService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Italy.TaxRegistrationId.Services.TaxRegistrationIdReceiptService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Italy.TaxRegistrationId.Services.TaxRegistrationIdReceiptService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Norway.Receipts.ReceiptNorwayService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Norway.Receipts.ReceiptNorwayService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Poland.TaxRegistrationId.Services.TaxRegistrationIdReceiptService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Poland.TaxRegistrationId.Services.TaxRegistrationIdReceiptService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Services.SaudiArabia.Services.ReceiptService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Services.SaudiArabia.Services.ReceiptService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ReceiptsAustria.ReceiptAustriaService (Microsoft.Dynamics.Commerce.Runtime.ReceiptsAustria.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ReceiptsAustria.ReceiptAustriaService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ReceiptsCzechia.ReceiptCzechiaService (Microsoft.Dynamics.Commerce.Runtime.ReceiptsCzechia.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ReceiptsCzechia.ReceiptCzechiaService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ReceiptsFrance.ReceiptFranceService (Microsoft.Dynamics.Commerce.Runtime.ReceiptsFrance.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ReceiptsFrance.ReceiptFranceService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ReceiptsGermany.ReceiptGermanyService (Microsoft.Dynamics.Commerce.Runtime.ReceiptsGermany.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ReceiptsGermany.ReceiptGermanyService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ReceiptsSaudiArabia.GetSalesTransactionCustomReceiptFieldService (Microsoft.Dynamics.Commerce.Runtime.ReceiptsSaudiArabia.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ReceiptsSaudiArabia.GetSalesTransactionCustomReceiptFieldService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ReceiptsSweden.ReceiptSwedenService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ReceiptsSweden.ReceiptSwedenService__Microsoft.Dynamics.Commerce.Runtime.Localization.Services.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.ReceiptsSweden.ReceiptSwedenService (Microsoft.Dynamics.Commerce.Runtime.ReceiptsSweden.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.ReceiptsSweden.ReceiptSwedenService__Microsoft.Dynamics.Commerce.Runtime.ReceiptsSweden.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.EmailReceiptService (Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.EmailReceiptService.md) | handler | [ComposeEmailServiceRequest](../by-request-type/ComposeEmailServiceRequest.md), [SendReceiptServiceRequest](../by-request-type/SendReceiptServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.FormattedReceiptService (Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.FormattedReceiptService.md) | handler | [GetReceiptsFromTenderLinesServiceRequest](../by-request-type/GetReceiptsFromTenderLinesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.FulfillmentLineStatusTrackingService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.FulfillmentLineStatusTrackingService.md) | handler | [MarkFulfillmentLinesAsPickedServiceRequest](../by-request-type/MarkFulfillmentLinesAsPickedServiceRequest.md), [MarkFulfillmentLinesAsPackedServiceRequest](../by-request-type/MarkFulfillmentLinesAsPackedServiceRequest.md), [MarkFulfillmentLinesAsShippedServiceRequest](../by-request-type/MarkFulfillmentLinesAsShippedServiceRequest.md), [MarkFulfillmentLinesAsPickupServiceRequest](../by-request-type/MarkFulfillmentLinesAsPickupServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.FulfillmentService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.FulfillmentService.md) | handler | [ShipFulfillmentLinesServiceRequest](../by-request-type/ShipFulfillmentLinesServiceRequest.md), [PickFulfillmentLinesServiceRequest](../by-request-type/PickFulfillmentLinesServiceRequest.md), [PackFulfillmentLinesServiceRequest](../by-request-type/PackFulfillmentLinesServiceRequest.md), [SearchFulfillmentLinesServiceRequest](../by-request-type/SearchFulfillmentLinesServiceRequest.md), [MapFulfillmentLinesToOperationsRequest](../by-request-type/MapFulfillmentLinesToOperationsRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.GetOrderManagementConfigurationServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.GetOrderManagementConfigurationServiceRequestHandler.md) | single_handler | [GetOrderManagementConfigurationServiceRequest](../by-request-type/GetOrderManagementConfigurationServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.GetOrderOriginatorsServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.GetOrderOriginatorsServiceRequestHandler.md) | single_handler | [GetOrderOriginatorsServiceRequest](../by-request-type/GetOrderOriginatorsServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.GetReceiptOutputTypeToAddressTypeMappingServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.GetReceiptOutputTypeToAddressTypeMappingServiceRequestHandler.md) | single_handler | [GetReceiptOutputTypeToAddressTypeMappingServiceRequest](../by-request-type/GetReceiptOutputTypeToAddressTypeMappingServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.GetReceiptTypesServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.GetReceiptTypesServiceRequestHandler.md) | single_handler | [GetReceiptTypesServiceRequest](../by-request-type/GetReceiptTypesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeSalesOrderAttributeProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeSalesOrderAttributeProvider.md) | single_handler | [ResolvePriceAttributeValuesServiceRequest](../by-request-type/ResolvePriceAttributeValuesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeSalesOrderProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeSalesOrderProvider.md) | single_handler | [ResolvePriceAttributeValuesServiceRequest](../by-request-type/ResolvePriceAttributeValuesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertySalesOrderAttributeProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertySalesOrderAttributeProvider.md) | single_handler | [ResolvePricingPropertyValuesServiceRequest](../by-request-type/ResolvePricingPropertyValuesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.ReceiptService (Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.ReceiptService.md) | handler | [GetReceiptServiceRequest](../by-request-type/GetReceiptServiceRequest.md), [GetEmailReceiptServiceRequest](../by-request-type/GetEmailReceiptServiceRequest.md), [PopulateTaxSummaryIndiaServiceRequest](../by-request-type/PopulateTaxSummaryIndiaServiceRequest.md), [GetReprintNumberServiceRequest](../by-request-type/GetReprintNumberServiceRequest.md), [GetReceiptFieldInfoFromTransactionServiceRequest](../by-request-type/GetReceiptFieldInfoFromTransactionServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService.md) | handler | [AddRefundableTenderLinesToSalesOrderRequest](../by-request-type/AddRefundableTenderLinesToSalesOrderRequest.md), [GetOrdersServiceRequest](../by-request-type/GetOrdersServiceRequest.md), [CreateSalesOrderServiceRequest](../by-request-type/CreateSalesOrderServiceRequest.md), [GetNextReceiptIdServiceRequest](../by-request-type/GetNextReceiptIdServiceRequest.md), [GenerateOrderNumberServiceRequest](../by-request-type/GenerateOrderNumberServiceRequest.md) (+21) |
| [Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Services.TaxIdentifiersReceiptService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Services.TaxIdentifiersReceiptService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.Services.TaxRegistrationIdReceiptService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.Services.TaxRegistrationIdReceiptService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.Services.TaxRegistrationIdReceiptService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.Services.TaxRegistrationIdReceiptService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.Services.TaxRegistrationIdReceiptService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.Services.TaxRegistrationIdReceiptService.md) | handler | [GetLocalizationCustomReceiptFieldServiceRequest](../by-request-type/GetLocalizationCustomReceiptFieldServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.TransactionService.FulfillmentTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TransactionService.FulfillmentTransactionService.md) | handler | [AcceptFulfillmentLinesRealtimeRequest](../by-request-type/AcceptFulfillmentLinesRealtimeRequest.md), [GetFulfillmentLinesRealtimeRequest](../by-request-type/GetFulfillmentLinesRealtimeRequest.md), [PickFulfillmentLinesRealtimeRequest](../by-request-type/PickFulfillmentLinesRealtimeRequest.md), [PackFulfillmentLinesRealtimeRequest](../by-request-type/PackFulfillmentLinesRealtimeRequest.md), [MarkFulfillmentLinesAsPackedRealtimeRequest](../by-request-type/MarkFulfillmentLinesAsPackedRealtimeRequest.md) (+5) |
| [Microsoft.Dynamics.Commerce.Runtime.TransactionService.SalesOrderTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TransactionService.SalesOrderTransactionService.md) | handler | [GetOrdersRealtimeRequest](../by-request-type/GetOrdersRealtimeRequest.md), [MarkReturnedItemsRealtimeRequest](../by-request-type/MarkReturnedItemsRealtimeRequest.md), [GetReturnLocationRealtimeRequest](../by-request-type/GetReturnLocationRealtimeRequest.md), [SearchJournalTransactionsRealtimeRequest](../by-request-type/SearchJournalTransactionsRealtimeRequest.md), [SearchSalesTransactionsByReceiptIdRealtimeRequest](../by-request-type/SearchSalesTransactionsByReceiptIdRealtimeRequest.md) (+8) |
| [Microsoft.Dynamics.Commerce.Runtime.TransactionService.TaskRecorderTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TransactionService.TaskRecorderTransactionService.md) | handler | [GetStorageAccessTokenForUploadRealtimeRequest](../by-request-type/GetStorageAccessTokenForUploadRealtimeRequest.md), [UploadRecordingRealtimeRequest](../by-request-type/UploadRecordingRealtimeRequest.md), [GenerateRecordingFileRealtimeRequest](../by-request-type/GenerateRecordingFileRealtimeRequest.md), [GenerateTrainingDocumentRealtimeRequest](../by-request-type/GenerateTrainingDocumentRealtimeRequest.md), [GenerateBusinessProcessModelPackageRealtimeRequest](../by-request-type/GenerateBusinessProcessModelPackageRealtimeRequest.md) (+6) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.CancelOrderRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.CancelOrderRequestHandler.md) | single_handler | [CancelOrderRequest](../by-request-type/CancelOrderRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.FilterSalesOrderByLookupCriteriaServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.FilterSalesOrderByLookupCriteriaServiceRequestHandler.md) | single_handler | [FilterSalesOrderByLookupCriteriaServiceRequest](../by-request-type/FilterSalesOrderByLookupCriteriaServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetOrdersRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetOrdersRequestHandler.md) | single_handler | [GetOrdersRequest](../by-request-type/GetOrdersRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetReceiptRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetReceiptRequestHandler.md) | single_handler | [GetReceiptRequest](../by-request-type/GetReceiptRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetReceiptTypesRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetReceiptTypesRequestHandler.md) | single_handler | [GetReceiptTypesRequest](../by-request-type/GetReceiptTypesRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetXAndZReportReceiptByCountryRegionRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetXAndZReportReceiptByCountryRegionRequestHandler.md) | single_handler | [GetXAndZReportReceiptByCountryRegionRequest](../by-request-type/GetXAndZReportReceiptByCountryRegionRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetXAndZReportReceiptRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetXAndZReportReceiptRequestHandler.md) | single_handler | [GetXAndZReportReceiptRequest](../by-request-type/GetXAndZReportReceiptRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.PickAndPackOrderRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.PickAndPackOrderRequestHandler.md) | single_handler | [PickAndPackOrderRequest](../by-request-type/PickAndPackOrderRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.RecalculateOrderRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.RecalculateOrderRequestHandler.md) | single_handler | [RecalculateOrderRequest](../by-request-type/RecalculateOrderRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.RemoveOrderPersonalDataServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.RemoveOrderPersonalDataServiceRequestHandler.md) | single_handler | [RemoveOrderPersonalDataServiceRequest](../by-request-type/RemoveOrderPersonalDataServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.SendReceiptRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.SendReceiptRequestHandler.md) | single_handler | [SendReceiptRequest](../by-request-type/SendReceiptRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.SubmitOrderRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.SubmitOrderRequestHandler.md) | single_handler | [CreateOrderFromCartRequest](../by-request-type/CreateOrderFromCartRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.SubmitSalesTransactionRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.SubmitSalesTransactionRequestHandler.md) | single_handler | [SubmitSalesTransactionRequest](../by-request-type/SubmitSalesTransactionRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.UpdateFulfillmentLocationsForSalesLinesServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.UpdateFulfillmentLocationsForSalesLinesServiceRequestHandler.md) | single_handler | [UpdateFulfillmentLocationsForSalesLinesServiceRequest](../by-request-type/UpdateFulfillmentLocationsForSalesLinesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.UploadOrderRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.UploadOrderRequestHandler.md) | single_handler | [UploadOrderRequest](../by-request-type/UploadOrderRequest.md) |

## Triggers (20)

| Trigger | Supported Requests |
|---------|--------------------|
| Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Triggers.GetReceiptRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll) | [GetReceiptRequest](../by-request-type/GetReceiptRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Triggers.PurgeSalesTransactionsDataTrigger (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll) | [PurgeSalesTransactionsDataRequest](../by-request-type/PurgeSalesTransactionsDataRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Triggers.SaveSalesTransactionDataRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll) | [SaveSalesTransactionDataRequest](../by-request-type/SaveSalesTransactionDataRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SalesOrderDataServiceTriggers (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll) | [GetSalesOrderDetailsDataRequest](../by-request-type/GetSalesOrderDetailsDataRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SalesTransactionDataServiceTriggers (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll) | [GetTransactionChageLinesDataRequest](../by-request-type/GetTransactionChageLinesDataRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Localization.Services.France.Receipts.GetReceiptFieldInfoFromTransactionRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll) | [GetReceiptFieldInfoFromTransactionServiceRequest](../by-request-type/GetReceiptFieldInfoFromTransactionServiceRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Localization.Services.France.Receipts.GetReceiptRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll) | [GetReceiptRequest](../by-request-type/GetReceiptRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Localization.Services.France.XZReports.GetReceiptServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll) | [GetReceiptServiceRequest](../by-request-type/GetReceiptServiceRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.Triggers.SalesOrderDataServiceTriggers (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll) | [GetSalesOrderDetailsDataRequest](../by-request-type/GetSalesOrderDetailsDataRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.Triggers.SalesTransactionDataServiceTriggers (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll) | [GetTransactionChageLinesDataRequest](../by-request-type/GetTransactionChageLinesDataRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Italy.TaxRegistrationId.Triggers.CreateSalesOrderServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll) | [CreateSalesOrderServiceRequest](../by-request-type/CreateSalesOrderServiceRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Norway.AuditEvent.PurgeSalesTransactionsDataTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll) | [PurgeSalesTransactionsDataRequest](../by-request-type/PurgeSalesTransactionsDataRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Poland.TaxRegistrationId.Triggers.CreateSalesOrderServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll) | [CreateSalesOrderServiceRequest](../by-request-type/CreateSalesOrderServiceRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Russia.CreateSalesOrderServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll) | [CreateSalesOrderServiceRequest](../by-request-type/CreateSalesOrderServiceRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Localization.Services.SaudiArabia.Triggers.CreateSalesOrderServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll) | [CreateSalesOrderServiceRequest](../by-request-type/CreateSalesOrderServiceRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.RegisterAuditEventNorway.PurgeSalesTransactionsDataTrigger (Microsoft.Dynamics.Commerce.Runtime.RegisterAuditEventNorway.dll) | [PurgeSalesTransactionsDataRequest](../by-request-type/PurgeSalesTransactionsDataRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.Triggers.CreateSalesOrderServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.dll) | [CreateSalesOrderServiceRequest](../by-request-type/CreateSalesOrderServiceRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.Triggers.CreateSalesOrderServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.dll) | [CreateSalesOrderServiceRequest](../by-request-type/CreateSalesOrderServiceRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateSalesOrderServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll) | [CreateSalesOrderServiceRequest](../by-request-type/CreateSalesOrderServiceRequest.md) |
| Microsoft.Dynamics.Commerce.Runtime.XZReportsFrance.GetReceiptServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.XZReportsFrance.dll) | [GetReceiptServiceRequest](../by-request-type/GetReceiptServiceRequest.md) |

## Request Types (157)

### AcceptFulfillmentLinesRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.AcceptFulfillmentLinesRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.FulfillmentTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `IEnumerable<FulfillmentLineParameter>` | FulfillmentLines |

### AddOrUpdateRemoteSalesOrderCacheDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.AddOrUpdateRemoteSalesOrderCacheDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Data.Services.SqlServer.RemoteSalesOrderCacheDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `SalesOrder` | SalesOrder |

### AddRefundableTenderLinesToSalesOrderRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AddRefundableTenderLinesToSalesOrderRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesOrder` | SalesOrder |

### AddTransferOrderCommentRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.AddTransferOrderCommentRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PickingReceivingService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | OrderId |
| `string` | CommentedBy |
| `string` | CommentText |

### AdjustInventoryBySalesTransactionServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AdjustInventoryBySalesTransactionServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryAdjustmentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | SalesTransaction |

### CalculateNonSalesTransactionRequiredReasonCodesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateNonSalesTransactionRequiredReasonCodesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ReasonCodeService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `NonSalesTransaction` | NonSalesTransaction |
| `NonSalesTransaction` | OriginalTransaction |
| `IEnumerable<ReasonCodeSourceType>` | SourceTypesToInclude |

### CalculateSalesTransactionServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateSalesTransactionServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CartService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `DiscountCalculationMode?` | DiscountCalculationMode |
| `bool?` | CalculateSimpleDiscountOnly |
| `CalculationModes?` | CalculationMode |
| `bool` | CalculatePricesForNewSalesLinesOnly |
| `HashSet<string>` | NewSalesLineIdSet |

### CancelOrderRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.CancelOrderRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.CancelOrderRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |
| `long?` | CartVersion |
| `string` | ReceiptEmailAddress |
| `string` | ReceiptNumberSequence |

### CancelSalesOrderServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CancelSalesOrderServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesOrdersLookupCriteria` | LookupCriteria |

### CheckAccessToOrdersServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessToOrdersServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.UserAuthenticationService (Microsoft.Dynamics.Commerce.Runtime.Services.Security.dll)
**Inherits:** CheckAccessServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<OrderOriginator>` | OrderOriginators |

### CheckInForOrderPickupServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckInForOrderPickupServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |
| `string` | PackingSlipId |
| `string` | ChannelReferenceId |
| `IEnumerable<CommerceProperty>` | OrderPickupAddtionalInformation |

### ConfirmPurchaseOrderRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.ConfirmPurchaseOrderRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryInboundOutboundDocumentTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | PurchaseOrderId |

### ConfirmPurchaseOrderServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ConfirmPurchaseOrderServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | SourceDocumentId |
| `InventorySourceDocumentType` | SourceDocumentType |

### ConfirmSalesOrderRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.ConfirmSalesOrderRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.SalesOrderTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | SalesId |

### ConfirmSalesOrderServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ConfirmSalesOrderServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | SalesId |

### ConvertSalesTransactionToOperationInputXmlRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.CustomerOrder.ConvertSalesTransactionToOperationInputXmlRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrderService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `SalesTransaction` | SalesTransaction |
| `SalesOrder` | TargetOrder |

### CreateChecklistTaskForOrderPickupServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateChecklistTaskForOrderPickupServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.TaskIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.Channels.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesOrder` | SalesOrder |
| `string` | PackingSlipId |
| `string` | ChannelReferenceId |
| `long` | ChannelId |
| `IEnumerable<CommerceProperty>` | OrderPickupAddtionalInformation |

### CreateSalesOrderServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateSalesOrderServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.CustomerOrderServiceTriggers (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.SaudiArabia.Triggers.CreateSalesOrderServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Russia.CreateSalesOrderServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Poland.TaxRegistrationId.Triggers.CreateSalesOrderServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Italy.TaxRegistrationId.Triggers.CreateSalesOrderServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.Triggers.CustomerOrderServiceTriggers (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.Triggers.CreateSalesOrderServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.dll), Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.Triggers.CreateSalesOrderServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.dll), Microsoft.Dynamics.Commerce.Runtime.Workflow.CreateSalesOrderServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### DeletePurchaseOrderLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeletePurchaseOrderLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventorySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | OrderId |

### DeleteTransferOrderLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteTransferOrderLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventorySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | OrderId |
| `IEnumerable<TransferOrderLine>` | TransferOrderLines |

### FillReceiptMaskServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.FillReceiptMaskServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | ReceiptMask |
| `string` | SeedValue |
| `string` | StoreId |
| `string` | TerminalId |
| `string` | StaffId |
| `DateTime` | CurrentDate |

### FilterSalesOrderByLookupCriteriaServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.FilterSalesOrderByLookupCriteriaServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.FilterSalesOrderByLookupCriteriaServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesOrder` | SalesOrder |
| `IEnumerable<ChannelReferenceAdditionalLookupCriteria>` | AdditionalLookupCriteria |

### GenerateOrderNumberServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GenerateOrderNumberServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | CharacterPool |

### GetAdjustedSalesOrderFiscalIntegrationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAdjustedSalesOrderFiscalIntegrationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesOrder` | SalesOrder |
| `FiscalIntegrationSalesOrderAdjustmentType` | AdjustmentType |

### GetChannelOrderManagementConfigurationDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChannelOrderManagementConfigurationDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ChannelDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |

### GetCurrentShiftNonSalesTransactionsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCurrentShiftNonSalesTransactionsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.NonSalesTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `NonSalesTransaction` | NonSalesTransaction |
| `string` | NonSalesTransactionId |

### GetCustomReceiptsRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomReceiptsRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentReceiptService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | TransactionId |
| `ReceiptRetrievalCriteria` | ReceiptRetrievalCriteria |

### GetEmailReceiptServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmailReceiptServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ReceiptService (Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesOrder` | SalesOrder |
| `ReadOnlyCollection<ReceiptType>` | ReceiptTypes |
| `bool` | IsCopy |
| `ReadOnlyCollection<TenderLine>` | TenderLines |
| `string` | ReceiptLayoutId |

### GetFiscalTextsFromSalesOrderFiscalIntegrationServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetFiscalTextsFromSalesOrderFiscalIntegrationServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrationService (Microsoft.Dynamics.Commerce.Runtime.Services.FiscalIntegrations.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesOrder` | SalesOrder |
| `string` | FiscalIntegrationFunctionalityProfileGroupId |

### GetFulfillmentGroupInventoryLocationsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetFulfillmentGroupInventoryLocationsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventoryLocationSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |
| `string` | DataAreaId |

### GetFulfillmentGroupMembersDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetFulfillmentGroupMembersDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.FulfillmentGroupDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | OwnerChannelId |
| `OrgUnitLocationSearchCriteria` | FilterCriteria |

### GetFulfillmentLinesByPackingSlipIdRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetFulfillmentLinesByPackingSlipIdRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.FulfillmentTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | SalesId |
| `string` | PackingSlipId |

### GetFulfillmentLinesRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetFulfillmentLinesRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.FulfillmentTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `FulfillmentLineSearchCriteria` | SearchCriteria |

### GetFulfillmentLinesUserAlertErrorsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetFulfillmentLinesUserAlertErrorsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.UserAlertService (Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ICollection<FulfillmentLineParameter>` | FulfillmentLines |
| `FulfillmentOperationType` | FulfillmentOperation |

### GetFulfillmentLinesUserAlertsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetFulfillmentLinesUserAlertsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.UserAlertService (Microsoft.Dynamics.Commerce.Runtime.Services.Utilities.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ICollection<FulfillmentLineParameter>` | FulfillmentLines |
| `FulfillmentOperationType` | FulfillmentOperation |

### GetInventoryAvailabilityForFulfillmentLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetInventoryAvailabilityForFulfillmentLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryAvailabilityService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | InventLocationId |
| `IEnumerable<FulfillmentLine>` | FulfillmentLines |

### GetInventoryAvailabilityForFulfillmentStoresServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetInventoryAvailabilityForFulfillmentStoresServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryAvailabilityService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `long` | ProductId |

### GetLatestFulfillmentLineTransactionsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLatestFulfillmentLineTransactionsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.Inventory.FulfillmentLineStatusSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ICollection<SalesLineReference>` | SalesLineReferences |

### GetLocalizationCustomReceiptFieldServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLocalizationCustomReceiptFieldServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentReceiptService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll), Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.GteReceiptService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.ReceiptsSweden.ReceiptSwedenService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.SaudiArabia.Services.ReceiptService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Poland.TaxRegistrationId.Services.TaxRegistrationIdReceiptService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Norway.Receipts.ReceiptNorwayService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Italy.TaxRegistrationId.Services.TaxRegistrationIdReceiptService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.TaxRegistrationId.Services.TaxRegistrationIdReceiptService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.Receipt.GteReceiptService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Germany.Receipts.ReceiptGermanyService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.France.Receipts.ReceiptFranceService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Czechia.Receipts.ReceiptCzechiaService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Austria.Receipts.ReceiptAustriaService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.ReceiptsAustria.ReceiptAustriaService (Microsoft.Dynamics.Commerce.Runtime.ReceiptsAustria.dll), Microsoft.Dynamics.Commerce.Runtime.ReceiptsCzechia.ReceiptCzechiaService (Microsoft.Dynamics.Commerce.Runtime.ReceiptsCzechia.dll), Microsoft.Dynamics.Commerce.Runtime.ReceiptsFrance.ReceiptFranceService (Microsoft.Dynamics.Commerce.Runtime.ReceiptsFrance.dll), Microsoft.Dynamics.Commerce.Runtime.ReceiptsGermany.ReceiptGermanyService (Microsoft.Dynamics.Commerce.Runtime.ReceiptsGermany.dll), Microsoft.Dynamics.Commerce.Runtime.ReceiptsSaudiArabia.GetSalesTransactionCustomReceiptFieldService (Microsoft.Dynamics.Commerce.Runtime.ReceiptsSaudiArabia.dll), Microsoft.Dynamics.Commerce.Runtime.ReceiptsSweden.ReceiptSwedenService (Microsoft.Dynamics.Commerce.Runtime.ReceiptsSweden.dll), Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Services.TaxIdentifiersReceiptService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.dll), Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.Services.TaxRegistrationIdReceiptService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.dll), Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.Services.TaxRegistrationIdReceiptService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.dll), Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.Services.TaxRegistrationIdReceiptService (Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.dll)
**Inherits:** GetCustomReceiptFieldServiceRequest

| Type | Property |
|------|----------|
| `SalesOrder` | SalesOrder |
| `SalesLine` | SalesLine |
| `TenderLine` | TenderLine |
| `TaxLine` | TaxLine |
| `CustomerAccountDepositLine` | CustomerAccountDepositLine |
| `IncomeExpenseLine` | IncomeExpenseLine |

### GetNextReceiptIdServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNextReceiptIdServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransactionType` | TransactionType |
| `ExtensibleSalesTransactionType` | ExtensibleSalesTransactionType |
| `CustomerOrderMode` | CustomerOrderMode |
| `decimal` | TotalAmount |
| `decimal` | NetAmountWithNoTax |
| `string` | ReceiptNumberSequence |

### GetNumberSequenceFromReceiptServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNumberSequenceFromReceiptServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | ReceiptMask |
| `string` | ReceiptId |

### GetOrderDeliveryOptionsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetOrderDeliveryOptionsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ShippingService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | SalesTransaction |
| `FilterDeliveryModeOption` | FilterOption |
| `bool` | IgnoreLinesWithDeliveryMode |

### GetOrderHistoryDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOrderHistoryDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.CustomerSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | CustomerAccountNumber |
| `DateTimeOffset` | StartDateTime |

### GetOrderHistoryRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetOrderHistoryRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.CustomerTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | CustomerAccountNumber |
| `DateTimeOffset` | StartDateTime |

### GetOrderHistoryServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetOrderHistoryServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | CustomerAccountNumber |

### GetOrderInvoiceRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetOrderInvoiceRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrderService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | InvoiceId |
| `string` | CustomerAccountNumber |

### GetOrderOriginatorsRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetOrderOriginatorsRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.SalesOrderTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `OrderOriginatorSearchCriteria` | OrderOriginatorSearchCriteria |

### GetOrderOriginatorsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetOrderOriginatorsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.GetOrderOriginatorsServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Workflow.DataAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `OrderOriginatorSearchCriteria` | OrderOriginatorSearchCriteria |

### GetOrderPickingListRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetOrderPickingListRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PickingReceivingService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `PurchaseTransferOrderType` | OrderType |
| `string` | SalesId |

### GetOrderShipmentsRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetOrderShipmentsRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.CustomerTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | CustomerAccountNumber |
| `DateTimeOffset` | StartDateTime |
| `bool` | EnableSkipForPaging |

### GetOrdersRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetOrdersRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.SalesOrderTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `SalesOrderSearchCriteria` | Criteria |

### GetOrdersRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetOrdersRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetOrdersRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowsAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `SalesOrderSearchCriteria` | Criteria |

### GetOrdersServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetOrdersServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesOrderSearchCriteria` | Criteria |

### GetProductAvailabilityForFulfillmentLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductAvailabilityForFulfillmentLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ProductAvailabilityService (Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | InventLocationId |
| `IEnumerable<FulfillmentLine>` | FulfillmentLines |

### GetProductInventoryAvailabilityForFulfillmentGroupDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductInventoryAvailabilityForFulfillmentGroupDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.Inventory.InventoryAvailabilitySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ProductId |

### GetProductRefinerValuesDisplayOrderByCatalogDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductRefinerValuesDisplayOrderByCatalogDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ProductSearchRefinementSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<long>` | RefinerIds |
| `long` | CatalogId |

### GetProductRefinerValuesDisplayOrderRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductRefinerValuesDisplayOrderRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ProductSearchRefinementSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<long>` | RefinerIds |

### GetPurchaseOrderDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPurchaseOrderDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.InventoryDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | OrderId |

### GetPurchaseOrderRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetPurchaseOrderRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PickingReceivingService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `PurchaseTransferOrderType` | OrderType |
| `string` | OrderId |

### GetReceiptFieldInfoFromTransactionServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptFieldInfoFromTransactionServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ReceiptService (Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.France.Receipts.GetReceiptFieldInfoFromTransactionRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `RequestContext` | Context |
| `ReceiptItemInfo` | ReceiptItemInfo |
| `ReceiptType` | ReceiptType |
| `SalesOrder` | SalesOrder |
| `TenderLine` | TenderLine |
| `GetCardPaymentPropertiesServiceResponse` | CardPaymentProperties |
| `bool` | IsCopy |
| `bool` | IsPreview |
| `string` | ExternalReceiptString |

### GetReceiptInfoDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReceiptInfoDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.SalesTransactionDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | LayoutId |
| `bool` | CopyReceipt |

### GetReceiptLayoutIdDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReceiptLayoutIdDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.SalesTransactionDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | ReceiptProfileId |
| `ReceiptType` | ReceiptType |

### GetReceiptMaskDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReceiptMaskDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.SalesTransactionDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | FunctionalityProfileId |
| `ReceiptTransactionType` | ReceiptTransactionType |

### GetReceiptMasksDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReceiptMasksDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.SalesTransactionDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ReceiptTransactionType?` | ReceiptTransactionType |

### GetReceiptNumberResetInfoRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReceiptNumberResetInfoRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ChannelDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | FunctionalityProfileId |

### GetReceiptRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetReceiptRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Triggers.GetReceiptRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.France.Receipts.GetReceiptRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | TransactionId |
| `TenderLine` | TenderLine |
| `IEnumerable<FulfillmentLineParameter>` | FulfillmentLines |
| `IEnumerable<decimal>` | SalesLineNumbers |
| `TransferOrderJournal` | TransferOrderJournal |
| `ReceiptRetrievalCriteria` | ReceiptRetrievalCriteria |
| `string` | SalesId |
| `string` | PackingSlipId |
| `InventoryDocumentReceiptSearchCriteria` | InventoryDocumentReceiptSearchCriteria |
| `CustomerOrderType` | CustomerOrderType |

### GetReceiptServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ReceiptService (Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll), Microsoft.Dynamics.Commerce.Runtime.XZReportsAustria.XZReportsAustriaService (Microsoft.Dynamics.Commerce.Runtime.XZReportsAustria.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.France.XZReports.GetReceiptServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Austria.XZReports.XZReportsAustriaService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.XZReportsFrance.GetReceiptServiceRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.XZReportsFrance.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
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

### GetReceiptTypesRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptTypesRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetReceiptTypesRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |

### GetReceiptTypesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptTypesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.GetReceiptTypesServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ReceiptType` | RequestedReceiptType |
| `SalesTransaction` | SalesTransaction |
| `bool` | SkipExclusion |

### GetReceiptsContentDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.DataServices.Messages.Internal.France.GetReceiptsContentDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.DataServices.Messages.Internal.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.France.ReceiptsContentDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TransactionId |
| `long` | ChannelId |
| `string` | TerminalId |
| `string` | StoreId |
| `string` | DataAreaId |

### GetReceiptsFromTenderLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptsFromTenderLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FormattedReceiptService (Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesOrder` | SalesOrder |
| `ReceiptInfo` | ReceiptInfo |
| `ReceiptType` | ReceiptType |
| `string` | HardwareProfileId |
| `bool` | IsCopy |
| `bool` | IsPreview |

### GetRemoteSalesOrderCacheDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetRemoteSalesOrderCacheDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Data.Services.SqlServer.RemoteSalesOrderCacheDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `TimeSpan` | CacheExpirationPeriod |
| `string` | TransactionId |
| `string` | CustomerId |
| `long` | ChannelId |

### GetSalesOrderByChannelReferenceLookupCriteriaDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesOrderByChannelReferenceLookupCriteriaDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.SalesOrderDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | ChannelReferenceId |
| `string` | CustomerId |
| `long?` | ChannelId |

### GetSalesOrderByChannelReferenceLookupCriteriaServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetSalesOrderByChannelReferenceLookupCriteriaServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ChannelReferenceLookupCriteria` | LookupCriteria |

### GetSalesOrderDetailsByChannelReferenceIdRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetSalesOrderDetailsByChannelReferenceIdRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.SalesOrderTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | ChannelReferenceId |
| `string` | CustomerId |

### GetSalesOrderDetailsByQuotationIdRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetSalesOrderDetailsByQuotationIdRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.SalesOrderTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | QuotationId |

### GetSalesOrderDetailsByQuotationIdServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetSalesOrderDetailsByQuotationIdServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | QuotationId |
| `SearchLocation` | SearchLocation |

### GetSalesOrderDetailsBySalesIdRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetSalesOrderDetailsBySalesIdRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.SalesOrderTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | SalesId |
| `string` | CustomerId |

### GetSalesOrderDetailsBySalesIdServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetSalesOrderDetailsBySalesIdServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | SalesId |
| `SearchLocation` | SearchLocation |

### GetSalesOrderDetailsByTransactionIdRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetSalesOrderDetailsByTransactionIdRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.SalesOrderTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | TransactionId |
| `string` | CustomerId |
| `long?` | ChannelId |

### GetSalesOrderDetailsByTransactionIdServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetSalesOrderDetailsByTransactionIdServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | TransactionId |
| `SearchLocation` | SearchLocation |

### GetSalesOrderDetailsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesOrderDetailsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.SalesOrderDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SalesOrderDataServiceTriggers (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.India.Triggers.SalesOrderDataServiceTriggers (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TransactionId |
| `string` | SalesId |
| `string` | CustomerId |
| `long?` | ChannelId |

### GetSalesOrderHeaderAttributeGroupsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesOrderHeaderAttributeGroupsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ChannelDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |

### GetSalesOrderLinesAttributeGroupsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesOrderLinesAttributeGroupsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ChannelDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |

### GetSalesOrdersByLookupCriteriaRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetSalesOrdersByLookupCriteriaRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.SalesOrderTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `SalesOrdersLookupCriteria` | LookupCriteria |

### GetSalesOrdersByLookupCriteriaServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetSalesOrdersByLookupCriteriaServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesOrdersLookupCriteria` | LookupCriteria |

### GetSalesOrdersWithNoFiscalTransactionDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesOrdersWithNoFiscalTransactionDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.FiscalTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | StoreNumber |
| `string` | TerminalId |

### GetSalesTransactionDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesTransactionDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.SalesTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `SalesOrderSearchCriteria` | SearchCriteria |

### GetSalesTransactionHashesForChargeCalculationRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetSalesTransactionHashesForChargeCalculationRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.AttributePricingService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `SimpleCustomer` | SimpleCustomer |

### GetSalesTransactionReadOnlyStatusDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesTransactionReadOnlyStatusDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.SalesTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TransactionId |

### GetSalesTransactionsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetSalesTransactionsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CartService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `CartSearchCriteria` | SearchCriteria |
| `bool` | MustRemoveUnavailableProductLines |

### GetTenderLinesForSalesOrderDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTenderLinesForSalesOrderDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.SalesTransactionDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TransactionId |

### GetTransferOrderCommentsRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetTransferOrderCommentsRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PickingReceivingService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | OrderId |

### GetTransferOrderDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTransferOrderDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.InventoryDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | OrderId |

### GetTransferOrderJournalDetailRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetTransferOrderJournalDetailRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PickingReceivingService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | OrderId |
| `string` | VoucherId |

### GetTransferOrderJournalsRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetTransferOrderJournalsRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PickingReceivingService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | OrderId |

### GetTransferOrderLinesRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetTransferOrderLinesRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PickingReceivingService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `PurchaseTransferOrderType` | OrderType |
| `string` | OrderId |
| `QueryResultSettings` | QuerySetting |

### GetTransferOrderRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.GetTransferOrderRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PickingReceivingService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `PurchaseTransferOrderType` | OrderType |
| `string` | OrderId |

### GetWarehouseForSalesTransactionRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetWarehouseForSalesTransactionRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.WarehouseService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### GetXAndZReportReceiptByCountryRegionRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetXAndZReportReceiptByCountryRegionRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetXAndZReportReceiptByCountryRegionRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | ShiftTerminalId |
| `long` | ShiftId |
| `ReceiptType` | ReceiptType |
| `string` | TransactionId |
| `string` | HardwareProfileId |
| `CountryRegionISOCode` | CountryRegionIsoCode |

### GetXAndZReportReceiptRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetXAndZReportReceiptRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Norway.XZReports.XZReportsNorwayService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Workflow.GetXAndZReportReceiptRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll), Microsoft.Dynamics.Commerce.Runtime.XZReportsNorway.XZReportsNorwayService (Microsoft.Dynamics.Commerce.Runtime.XZReportsNorway.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowsAuthorizationTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | ShiftTerminalId |
| `long` | ShiftId |
| `ReceiptType` | ReceiptType |
| `string` | TransactionId |
| `string` | HardwareProfileId |

### InsertFulfillmentLineTransactionsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertFulfillmentLineTransactionsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.Inventory.FulfillmentLineStatusSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ICollection<FulfillmentLineTransaction>` | FulfillmentLineTransactions |

### InsertReceiptsContentDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.DataServices.Messages.Internal.France.InsertReceiptsContentDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.DataServices.Messages.Internal.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.France.ReceiptsContentDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TransactionId |
| `long` | ChannelId |
| `string` | TerminalId |
| `string` | StoreId |
| `string` | DataAreaId |
| `string` | Content |

### InsertSalesTransactionTablesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertSalesTransactionTablesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.SalesTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `DataTable` | TransactionTable |
| `DataTable` | MarkupTable |
| `DataTable` | TaxTable |
| `DataTable` | ChargeTaxTable |
| `DataTable` | PaymentTable |
| `DataTable` | LinesTable |
| `DataTable` | WarrantyLinesTable |
| `DataTable` | IncomeExpenseTable |
| `DataTable` | AttributeTable |
| `DataTable` | AddressTable |
| `DataTable` | DiscountTable |
| `DataTable` | PriceTable |
| `DataTable` | ReasonCodeTable |
| `DataTable` | PropertiesTable |
| `DataTable` | AffiliationsTable |
| `DataTable` | RewardPointTable |
| `DataTable` | CustomerOrderTable |
| `DataTable` | InvoiceTable |
| `DataTable` | CustomerAccountDepositTable |
| `bool` | ShouldIncrementGrandTotals |
| `DataTable` | FiscalTransactionTable |
| `DataTable` | FiscalTransPaymentTransAdjustmentTable |
| `DataTable` | FiscalTransSalesLineAdjustmentTable |
| `DataTable` | FiscalTransExtendedDataTable |
| `DataTable` | SalesAgreementLinesTable |
| `DataTable` | NoteTable |

### InvokeOrderAsynchronousOperationRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.InvokeOrderAsynchronousOperationRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### MapFulfillmentLinesToOperationsRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.MapFulfillmentLinesToOperationsRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FulfillmentService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IReadOnlyCollection<FulfillmentLine>` | FulfillmentLines |

### MapSalesOrdersToOperationsRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.MapSalesOrdersToOperationsRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IReadOnlyCollection<SalesOrder>` | SalesOrders |

### MarkFulfillmentLinesAsPackedRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.MarkFulfillmentLinesAsPackedRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.FulfillmentTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `IEnumerable<FulfillmentLineParameter>` | FulfillmentLines |

### PackFulfillmentLinesRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.PackFulfillmentLinesRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.FulfillmentTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `IEnumerable<FulfillmentLineParameter>` | FulfillmentLines |

### PackFulfillmentLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PackFulfillmentLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FulfillmentService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ICollection<FulfillmentLineParameter>` | FulfillmentLines |

### PickAndPackOrderRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.PickAndPackOrderRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrderService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | SalesId |
| `bool` | CreatePickingList |
| `bool` | CreatePackingSlip |
| `long` | ChannelId |
| `string` | InventoryLocationId |
| `IEnumerable<PickAndPackSalesLineParameter>` | SalesLineParameters |

### PickAndPackOrderRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.PickAndPackOrderRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.PickAndPackOrderRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | SalesId |
| `bool` | CreatePickingList |
| `bool` | CreatePackingSlip |
| `IEnumerable<PickAndPackSalesLineParameter>` | SalesLineParameters |

### PickFulfillmentLinesRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.PickFulfillmentLinesRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.FulfillmentTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `IEnumerable<FulfillmentLineParameter>` | FulfillmentLines |

### PickFulfillmentLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PickFulfillmentLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FulfillmentService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ICollection<FulfillmentLineParameter>` | FulfillmentLines |

### PopulateSalesTransactionWithTaxesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PopulateSalesTransactionWithTaxesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.TaxCalculationRequestHandler (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ITaxDocument` | TaxDocument |
| `TaxableDocumentMapping` | DocumentMapping |

### PurgeSalesTransactionsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.PurgeSalesTransactionsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.SalesTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Triggers.PurgeSalesTransactionsDataTrigger (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Norway.AuditEvent.PurgeSalesTransactionsDataTrigger (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.RegisterAuditEventNorway.PurgeSalesTransactionsDataTrigger (Microsoft.Dynamics.Commerce.Runtime.RegisterAuditEventNorway.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |
| `string` | TerminalId |
| `int` | RetentionDays |

### RecalculateOrderRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.RecalculateOrderRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.RecalculateOrderRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |

### RejectFulfillmentLinesRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.RejectFulfillmentLinesRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.FulfillmentTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `IEnumerable<RejectFulfillmentLine>` | FulfillmentLines |

### RemoveOrderPersonalDataServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.RemoveOrderPersonalDataServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.RemoveOrderPersonalDataServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesOrder` | SalesOrder |

### RemoveRemoteSalesOrderCacheDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.RemoveRemoteSalesOrderCacheDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Data.Services.SqlServer.RemoteSalesOrderCacheDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TransactionId |

### SaveNonSalesTransactionDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveNonSalesTransactionDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.NonSalesTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `NonSalesTransaction` | NonSalesTransaction |

### SavePurchaseOrderLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SavePurchaseOrderLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventorySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `PurchaseOrder` | PurchaseOrder |

### SavePurchaseOrderRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.SavePurchaseOrderRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PickingReceivingService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `bool` | Commit |
| `PurchaseOrder` | PurchaseOrder |

### SaveSalesTransactionDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveSalesTransactionDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.SalesTransactionDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll), Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.SaveGteTaxDataRequestHandler (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.SaveGteTaxDataRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Norway.XZReports.XZReportsNorwaySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll), Microsoft.Dynamics.Commerce.Runtime.XZReportsNorway.XZReportsNorwaySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.XZReportsNorway.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Triggers.SaveSalesTransactionDataRequestTrigger (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `SalesTransaction` | SalesTransaction |

### SaveTransferOrderDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveTransferOrderDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.InventorySqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `TransferOrder` | TransferOrder |

### SaveTransferOrderRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.SaveTransferOrderRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PickingReceivingService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `bool` | Commit |
| `TransferOrder` | TransferOrder |
| `bool` | SkipNotValidLines |

### SearchFulfillmentLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SearchFulfillmentLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FulfillmentService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `FulfillmentLineSearchCriteria` | Criteria |

### SearchOrdersRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.SearchOrdersRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.SalesOrderTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `OrderSearchCriteria` | Criteria |

### SearchOrdersServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SearchOrdersServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `OrderSearchCriteria` | Criteria |

### SearchSalesOrdersHeaderDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchSalesOrdersHeaderDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Data.Services.SqlServer.SalesOrderSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `long` | ChannelId |
| `string` | TransactionId |
| `string` | SalesId |
| `string` | ReceiptId |
| `string` | ChannelReferenceId |
| `string` | CustomerName |
| `string` | CustomerAccountNumber |
| `string` | Store |
| `string` | TerminalId |
| `string` | StaffId |
| `DateTimeOffset?` | StartDateTime |
| `DateTimeOffset?` | EndDateTime |
| `string` | EmailAddress |
| `string` | LoyaltyCardNumber |
| `string` | CustomerPhoneNumber |
| `string` | CustomerRequisition |
| `IEnumerable<SalesTransactionType>` | SalesTransactionTypes |
| `IEnumerable<ExtensibleSalesTransactionType>` | ExtensibleSalesTransactionTypes |
| `IEnumerable<SalesStatus>` | OrderStatus |
| `ICollection<string>` | CustomTransactionIds |
| `string` | BusinessPartnerId |
| `ICollection<long>` | ChannelIds |

### SearchSalesTransactionDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchSalesTransactionDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.SalesTransactionDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `SalesOrderSearchCriteria` | SearchCriteria |

### SearchSalesTransactionsByReceiptIdRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.SearchSalesTransactionsByReceiptIdRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.SalesOrderTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | ReceiptId |

### SearchSalesTransactionsByReceiptIdServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SearchSalesTransactionsByReceiptIdServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | ReceiptId |

### SendReceiptRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.SendReceiptRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.SendReceiptRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `SearchReceiptCriteria` | SearchReceiptCriteria |
| `ICollection<ElectronicAddress>` | RecipientAddresses |

### SendReceiptServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SendReceiptServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.EmailReceiptService (Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesOrder` | SalesOrder |
| `ReadOnlyCollection<ReceiptType>` | ReceiptTypes |
| `bool` | IsCopy |
| `ReadOnlyCollection<ElectronicAddress>` | RecipientAddresses |

### SequentialSignatureSalesOrderAdjustmentRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DocumentProvider.SequentialSignature.Common.Messages.SequentialSignatureSalesOrderAdjustmentRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DocumentProvider.SequentialSignature.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DocumentProvider.SequentialSignature.SequentialSignatureSalesOrderAdjustmentService (Microsoft.Dynamics.Commerce.Runtime.DocumentProvider.SequentialSignature.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesOrder` | SalesOrder |

### SetSalesTransactionReadOnlyStatusDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SetSalesTransactionReadOnlyStatusDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.SalesTransactionSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `SalesTransactionReadOnlyStatus` | ReadOnlyStatus |
| `SalesTransaction` | SalesTransaction |

### SettleOrderInvoiceRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.SettleOrderInvoiceRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrderService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `string` | SalesTransactionId |
| `string` | InvoiceId |
| `decimal` | InvoiceAmount |
| `InvoiceType` | InvoiceType |

### ShipFulfillmentLinesRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.ShipFulfillmentLinesRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.FulfillmentTransactionService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `IEnumerable<ShipFulfillmentLine>` | FulfillmentLines |

### ShipFulfillmentLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ShipFulfillmentLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.FulfillmentService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `IEnumerable<ShipFulfillmentLine>` | FulfillmentLines |

### SubmitSalesTransactionRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.SubmitSalesTransactionRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.SubmitSalesTransactionRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |
| `long?` | CartVersion |
| `string` | CustomerAccountNumber |
| `string` | ReceiptEmail |
| `string` | ReceiptNumberSequence |

### TransferOrderLineOperationRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.TransferOrderLineOperationRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PickingReceivingService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** TransferOrderRealtimeRequestBase

| Type | Property |
|------|----------|
| `string` | TransferOrderId |
| `IEnumerable<TransferOrderLine>` | TransferOrderLines |

### TransferOrderOperationRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.TransferOrderOperationRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PickingReceivingService (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** TransferOrderRealtimeRequestBase

| Type | Property |
|------|----------|
| `TransferOrder` | TransferOrder |

### UpdateFulfillmentLocationsForSalesLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateFulfillmentLocationsForSalesLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.UpdateFulfillmentLocationsForSalesLinesServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### UpdateInventoryInboundOutboundDocumentReceiptIdRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateInventoryInboundOutboundDocumentReceiptIdRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | DocumentId |
| `string` | ReceiptId |
| `long?` | DocumentVersion |

### UploadOrderRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.UploadOrderRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.UploadOrderRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `SalesOrder` | Order |

### ValidateCouponUsageInOrderServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateCouponUsageInOrderServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CouponService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### ValidateFiscalDocumentRefReceiptNumberLengthDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.DataServices.Messages.ValidateFiscalDocumentRefReceiptNumberLengthDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.FiscalDocumentValidationService (Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `FiscalDocument` | FiscalDocument |

### ValidateInventoryPurchaseOrderLineOverreceiveRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateInventoryPurchaseOrderLineOverreceiveRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `InventoryInboundOutboundDocumentLine` | Line |
| `decimal` | NewQuantity |
| `decimal` | AllowedQuantity |
| `decimal` | PreviousQuantity |
| `InventoryInboundOutboundDocumentUpdateLinesSourceType` | SourceType |

### ValidateInventoryPurchaseOrderLineUnderReceivingRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateInventoryPurchaseOrderLineUnderReceivingRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `InventoryInboundOutboundDocument` | Document |
| `InventoryInboundOutboundDocumentLine` | Line |
| `InventoryInboundOutboundDocumentOperationType` | OperationType |

### ValidateInventoryTransferOrderLineOvershipRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateInventoryTransferOrderLineOvershipRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `InventoryInboundOutboundDocumentLine` | Line |
| `decimal` | NewQuantity |
| `decimal` | AllowedQuantity |
| `decimal` | PreviousQuantity |
| `InventoryInboundOutboundDocumentUpdateLinesSourceType` | SourceType |

### ValidateInventoryTransferOrderLineUnderDeliveryRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateInventoryTransferOrderLineUnderDeliveryRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.InventoryDocumentService (Microsoft.Dynamics.Commerce.Runtime.Services.Inventory.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `InventoryInboundOutboundDocumentLine` | Line |
| `InventoryInboundOutboundDocumentOperationType` | OperationType |

### ValidatePartiallyFulfilledOrderUpdateServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidatePartiallyFulfilledOrderUpdateServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrderValidationService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `Cart` | UpdatedCart |
| `IEnumerable<CartLine>` | UpdatedCartLines |
| `SalesTransaction` | ExistingTransaction |

### ValidatePendingOrderTenderLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidatePendingOrderTenderLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PaymentManagerService (Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<CartTenderLine>` | TenderLines |

### ValidatePrintReceiptCopyAllowedServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidatePrintReceiptCopyAllowedServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesOrder` | SalesOrderToPrint |

### ValidateSalesTransactionInvoiceIdLengthDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateSalesTransactionInvoiceIdLengthDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.SalesTransactionDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### ValidateSalesTransactionServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateSalesTransactionServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
