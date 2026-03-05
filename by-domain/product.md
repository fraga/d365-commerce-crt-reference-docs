# Product

## Handlers (52)

| Handler | Kind | Assembly | Supported Requests |
|---------|------|----------|--------------------|
| BarcodeDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetBarcodeMaskSegmentDataRequest, GetBarcodeMaskDataRequest |
| BarcodeService | handler | Microsoft.Dynamics.Commerce.Runtime.ElectronicReporting.dll | EncodeBarcodeServiceRequest, Microsoft.Dynamics.Commerce.Runtime.Services.Messages.EncodeQrCodeServiceRequest, Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Messages.EncodeQrCodeServiceRequest |
| BarcodeService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll | ProcessMaskSegmentsServiceRequest, GetBarcodeTypeServiceRequest, CalculateQuantityFromPriceServiceRequest |
| BeginReadChangedProductsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | BeginReadChangedProductsRequest |
| DeleteListingsByCatalogsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | DeleteListingsByCatalogsRequest |
| EndReadChangedProductsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | EndReadChangedProductsRequest |
| GetBarcodeRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetBarcodeRequest |
| GetChangedProductsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | ChangedProductsSearchRequest |
| GetDeletedCatalogsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetDeletedCatalogsRequest |
| GetItemByIdRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetItemByIdRequest |
| GetProductDeliveryOptionsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetProductDeliveryOptionsRequest |
| GetRecommendationsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetRecommendedElementsRequest |
| GetRelatedProductsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetRelatedProductsRequest |
| ItemDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll |  |
| ItemSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetItemsDataRequest, CheckIfProductOrVariantAreInCategoryDataRequest, GetProductVariantsDataRequest, GetBarcodesByInventoryDimensionDataRequest |
| MediaStorageSecurityTransactionService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | AssociateSasKeyRealtimeRequest |
| ProductAttributeService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll | GetProductAttributeValuesServiceRequest, GetAttributeValuesByProductIdsServiceRequest |
| ProductAttributesSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll |  |
| ProductAvailabilityService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll | GetStoreAvailabilityServiceRequest, GetItemAvailabilitiesByItemsServiceRequest, GetItemAvailabilitiesByItemQuantitiesServiceRequest, GetItemAvailabilitiesByItemWarehousesServiceRequest, GetItemAvailableQuantitiesByItemsServiceRequest (+4) |
| ProductAvailabilitySqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetItemAvailabilitiesDataRequest, ReleaseItemsDataRequest, ReserveItemsDataRequest |
| ProductComparisonService | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll | GetProductComparisonServiceRequest |
| ProductDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll |  |
| ProductDimensionSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll |  |
| ProductGteSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.India.GetItemTaxInformationDataRequest, Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemTaxInformationDataRequest |
| ProductGteSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll | GetItemTaxInformationDataRequest |
| ProductKitService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll | GetProductKitComponentServiceRequest |
| ProductKitSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll |  |
| ProductListService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll | SaveProductListServiceRequest, CopyCartToProductListServiceRequest, GetProductListsServiceRequest, GetProductListLinesServiceRequest |
| ProductListSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | SaveProductListDataRequest, SaveProductListLinesDataRequest, SearchProductListsDataRequest, SearchProductListLinesDataRequest, GetProductListDataRequest (+2) |
| ProductMediaSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll |  |
| ProductRecommendationService | handler | Microsoft.Dynamics.Commerce.Runtime.RecommendationServices.dll |  |
| ProductRecommendationTransactionService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetRecommendationServiceCredentialsRealtimeRequest |
| ProductRelationsSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll |  |
| ProductSearchAzureService | handler | Microsoft.Dynamics.Commerce.Runtime.SearchServices.Azure.dll | GetProductSearchResultsServiceRequest, GetProductSearchSuggestionsServiceRequest, GetProductSearchRefinersServiceRequest |
| ProductSearchBingService | handler | Microsoft.Dynamics.Commerce.Runtime.SearchServices.Bing.dll | GetProductSearchResultsServiceRequest, GetProductSearchSuggestionsServiceRequest, GetProductSearchRefinersServiceRequest |
| ProductSearchHandler | handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | SearchProductsRequest, GetProductSearchSuggestionsRequest, GetProductSearchRefinerValuesRequest, GetProductSearchRefinersRequest, GetSearchConfigurationRequest (+1) |
| ProductSearchRefinementSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetChannelProductRefinersDataRequest, GetCatalogProductRefinersDataRequest, GetProductRefinersByCategoryDataRequest, GetProductRefinersByTextDataRequest, GetProductRefinerValuesByCategoryDataRequest (+5) |
| ProductSearchSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetProductSearchResultsByProductIdsDataRequest, GetProductSearchResultsDataRequest, GetProductSearchSuggestionsDataRequest, GetProductSearchTypeDataRequest |
| ProductService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll |  |
| ProductSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll |  |
| ProductTransactionServiceRequestHandler | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetProductDataRealtimeRequest, GetRemoteProductsByCategoryRealtimeRequest, GetRemoteProductsByKeywordRealtimeRequest, RemoteSearchProductsRealtimeRequest, GetRemoteProductVariantCountRealtimeRequest |
| ProductsService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll |  |
| ProductsSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll |  |
| RecommendationsDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetRecommendationsDataRequest |
| RecommendationsService | handler | Microsoft.Dynamics.Commerce.Runtime.RecommendationServices.dll |  |
| RecommendationsSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetRecommendationByIdDataRequest, GetRecommendedElementsDataRequest |
| SearchProductsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | ProductSearchRequest |
| SearchProductsService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll |  |
| SearchRecommendationsHandler | handler | Microsoft.Dynamics.Commerce.Runtime.RecommendationServices.dll |  |
| SimpleProductDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetProductDimensionsDataRequest |
| VerifyProductExistenceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | VerifyProductExistenceRequest |
| WarrantyProductSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetApplicableWarrantyIdsDataRequest, ValidateWarrantyAssociationDataRequest, GetWarrantiesDataRequest |

## Triggers (2)

| Trigger | Assembly | Supported Requests |
|---------|----------|--------------------|
| GetTaxableItemTaxCodesPostProcessingTrigger | Microsoft.Dynamics.Commerce.Runtime.TaxServiceIndia.dll | GetTaxableItemTaxCodesServiceRequest |
| PrependAzureCmsMediaBaseUrlTrigger | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetProductMediaLocationsDataRequest, SearchMediaLocationsDataRequest, GetRelatedProductsDataRequest, GetProductsDataRequest, GetProductSearchResultsByProductIdsDataRequest, RefineProductSearchByCategoryDataRequest, RefineProductSearchByTextDataRequest, GetProductSearchResultsDataRequest, GetProductSwatchOverridesDataRequest, GetPurchaseHistoryDataRequest, GetProductSearchResultsServiceRequest, GetProductSearchSuggestionsServiceRequest, GetChannelCategoriesDataRequest, GetDirectChildCategoriesDataRequest |
