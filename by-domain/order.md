# Order

## Handlers (62)

| Handler | Kind | Assembly | Supported Requests |
|---------|------|----------|--------------------|
| CancelOrderRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | CancelOrderRequest |
| EmailReceiptService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll | ComposeEmailServiceRequest, SendReceiptServiceRequest |
| FilterSalesOrderByLookupCriteriaServiceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | FilterSalesOrderByLookupCriteriaServiceRequest |
| FiscalDocumentReceiptService | handler | Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll | GetLocalizationCustomReceiptFieldServiceRequest, GetCustomReceiptsRequest |
| FormattedReceiptService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll | GetReceiptsFromTenderLinesServiceRequest |
| FulfillmentGroupDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetFulfillmentGroupMembersDataRequest |
| FulfillmentLineStatusSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetLatestFulfillmentLineTransactionsDataRequest, InsertFulfillmentLineTransactionsDataRequest, GetSalesLineReferenceLookupsDataRequest, InsertSalesLineReferenceLookupsDataRequest |
| FulfillmentLineStatusTrackingService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | MarkFulfillmentLinesAsPickedServiceRequest, MarkFulfillmentLinesAsPackedServiceRequest, MarkFulfillmentLinesAsShippedServiceRequest, MarkFulfillmentLinesAsPickupServiceRequest |
| FulfillmentService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | ShipFulfillmentLinesServiceRequest, PickFulfillmentLinesServiceRequest, PackFulfillmentLinesServiceRequest, SearchFulfillmentLinesServiceRequest, MapFulfillmentLinesToOperationsRequest |
| FulfillmentTransactionService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | AcceptFulfillmentLinesRealtimeRequest, GetFulfillmentLinesRealtimeRequest, PickFulfillmentLinesRealtimeRequest, PackFulfillmentLinesRealtimeRequest, MarkFulfillmentLinesAsPackedRealtimeRequest (+5) |
| GetOrderManagementConfigurationServiceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | GetOrderManagementConfigurationServiceRequest |
| GetOrderOriginatorsServiceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | GetOrderOriginatorsServiceRequest |
| GetOrdersRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetOrdersRequest |
| GetReceiptOutputTypeToAddressTypeMappingServiceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll | GetReceiptOutputTypeToAddressTypeMappingServiceRequest |
| GetReceiptRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetReceiptRequest |
| GetReceiptTypesRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetReceiptTypesRequest |
| GetReceiptTypesServiceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll | GetReceiptTypesServiceRequest |
| GetSalesTransactionCustomReceiptFieldService | handler | Microsoft.Dynamics.Commerce.Runtime.ReceiptsSaudiArabia.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| GetXAndZReportReceiptRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetXAndZReportReceiptRequest |
| GteReceiptService | handler | Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll | GetLocalizationCustomReceiptFieldServiceRequest, PopulateTaxSummaryIndiaServiceRequest, GetFormattedNumberServiceRequest |
| GteReceiptService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetLocalizationCustomReceiptFieldServiceRequest, PopulateTaxSummaryIndiaServiceRequest, GetFormattedNumberServiceRequest |
| NonSalesTransactionSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | SaveNonSalesTransactionDataRequest, GetCurrentShiftNonSalesTransactionsDataRequest, GetStoreSafeDataRequest, GetTransactionTenderTypeDataRequest |
| PickAndPackOrderRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | PickAndPackOrderRequest |
| PricingPropertySalesOrderAttributeProvider | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll | ResolvePricingPropertyValuesServiceRequest |
| RecalculateOrderRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | RecalculateOrderRequest |
| ReceiptAustriaService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| ReceiptAustriaService | handler | Microsoft.Dynamics.Commerce.Runtime.ReceiptsAustria.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| ReceiptCzechiaService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| ReceiptCzechiaService | handler | Microsoft.Dynamics.Commerce.Runtime.ReceiptsCzechia.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| ReceiptFranceService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| ReceiptFranceService | handler | Microsoft.Dynamics.Commerce.Runtime.ReceiptsFrance.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| ReceiptGermanyService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| ReceiptGermanyService | handler | Microsoft.Dynamics.Commerce.Runtime.ReceiptsGermany.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| ReceiptNorwayService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| ReceiptService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| ReceiptService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Receipts.dll | GetReceiptServiceRequest, GetEmailReceiptServiceRequest, PopulateTaxSummaryIndiaServiceRequest, GetReprintNumberServiceRequest |
| ReceiptSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetEmailReceiptSettingsDataRequest |
| ReceiptSwedenService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| ReceiptSwedenService | handler | Microsoft.Dynamics.Commerce.Runtime.ReceiptsSweden.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| RemoteSalesOrderCacheDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | AddOrUpdateRemoteSalesOrderCacheDataRequest, GetRemoteSalesOrderCacheDataRequest, RemoveRemoteSalesOrderCacheDataRequest |
| RemoveOrderPersonalDataServiceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | RemoveOrderPersonalDataServiceRequest |
| SalesOrderDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetSalesOrderDetailsDataRequest, GetSalesOrderByChannelReferenceLookupCriteriaDataRequest, GetCustomerOrderParametersDataRequest, SearchSalesOrdersHeaderDataRequest |
| SalesOrderService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | AddRefundableTenderLinesToSalesOrderRequest, GetOrdersServiceRequest, CreateSalesOrderServiceRequest, GetNextReceiptIdServiceRequest, GenerateOrderNumberServiceRequest (+17) |
| SalesOrderTransactionService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetOrdersRealtimeRequest, MarkReturnedItemsRealtimeRequest, GetReturnLocationRealtimeRequest, SearchJournalTransactionsRealtimeRequest, SearchSalesTransactionsByReceiptIdRealtimeRequest (+6) |
| SalesTransactionAdjustmentsDataService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll | InsertSalesTransAdjustmentsDataRequest |
| SalesTransactionDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | SaveSalesTransactionDataRequest, SearchSalesTransactionDataRequest, GetReceiptMaskDataRequest, GetReceiptMasksDataRequest, GetTenderLinesForSalesOrderDataRequest (+7) |
| SalesTransactionSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetCartsDataRequest, SaveCartVersionedDataRequest, SaveCartDataRequest, DeleteCartDataRequest, InsertSalesTransactionTablesDataRequest (+14) |
| SendReceiptRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | SendReceiptRequest |
| SequentialSignatureSalesOrderAdjustmentService | handler | Microsoft.Dynamics.Commerce.Runtime.DocumentProvider.SequentialSignature.dll | SequentialSignatureSalesOrderAdjustmentRequest |
| SubmitOrderRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | CreateOrderFromCartRequest |
| SubmitSalesTransactionRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | SubmitSalesTransactionRequest |
| TaskRecorderTransactionService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetStorageAccessTokenForUploadRealtimeRequest, UploadRecordingRealtimeRequest, GenerateRecordingFileRealtimeRequest, GenerateTrainingDocumentRealtimeRequest, GenerateBusinessProcessModelPackageRealtimeRequest (+6) |
| TaxIdentifiersReceiptService | handler | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| TaxRegistrationIdReceiptService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| TaxRegistrationIdReceiptService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| TaxRegistrationIdReceiptService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| TaxRegistrationIdReceiptService | handler | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| TaxRegistrationIdReceiptService | handler | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| TaxRegistrationIdReceiptService | handler | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.dll | GetLocalizationCustomReceiptFieldServiceRequest |
| UpdateFulfillmentLocationsForSalesLinesServiceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | UpdateFulfillmentLocationsForSalesLinesServiceRequest |
| UploadOrderRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | UploadOrderRequest |
| WarrantySalesTransactionSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetWarrantyTransactionsDataRequest |

## Triggers (18)

| Trigger | Assembly | Supported Requests |
|---------|----------|--------------------|
| CreateSalesOrderServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | CreateSalesOrderServiceRequest |
| CreateSalesOrderServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | CreateSalesOrderServiceRequest |
| CreateSalesOrderServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | CreateSalesOrderServiceRequest |
| CreateSalesOrderServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | CreateSalesOrderServiceRequest |
| CreateSalesOrderServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.dll | CreateSalesOrderServiceRequest |
| CreateSalesOrderServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.dll | CreateSalesOrderServiceRequest |
| CreateSalesOrderServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | CreateSalesOrderServiceRequest |
| GetReceiptRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll | GetReceiptRequest |
| GetReceiptServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetReceiptServiceRequest |
| GetReceiptServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.XZReportsFrance.dll | GetReceiptServiceRequest |
| PurgeSalesTransactionsDataTrigger | Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll | PurgeSalesTransactionsDataRequest |
| PurgeSalesTransactionsDataTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | PurgeSalesTransactionsDataRequest |
| PurgeSalesTransactionsDataTrigger | Microsoft.Dynamics.Commerce.Runtime.RegisterAuditEventNorway.dll | PurgeSalesTransactionsDataRequest |
| SalesOrderDataServiceTriggers | Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll | GetSalesOrderDetailsDataRequest |
| SalesOrderDataServiceTriggers | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetSalesOrderDetailsDataRequest |
| SalesTransactionDataServiceTriggers | Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll | GetTransactionChageLinesDataRequest |
| SalesTransactionDataServiceTriggers | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetTransactionChageLinesDataRequest |
| SaveSalesTransactionDataRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll | SaveSalesTransactionDataRequest |
