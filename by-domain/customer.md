# Customer

## Handlers (45)

| Handler | Kind | Assembly | Supported Requests |
|---------|------|----------|--------------------|
| BusinessPartnerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll |  |
| BusinessPartnerService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Customers.dll | CreateBusinessPartnerUserServiceRequest, UpdateBusinessPartnerUserServiceRequest, RemoveBusinessPartnerUserServiceRequest, GetCurrentBusinessPartnerServiceRequest, GetCurrentBusinessPartnerUserServiceRequest (+8) |
| BusinessPartnerSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | CreateBusinessPartnerProspectDataRequest, CreateBusinessPartnerUserDataRequest, UpdateBusinessPartnerUserDataRequest, RemoveBusinessPartnerUserDataRequest, GetCurrentBusinessPartnerDataRequest (+9) |
| BusinessPartnerTransactionServiceRequestHandlerAsync | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetBusinessPartnerOrderHistoryRealtimeRequest |
| CreateCustomerRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | CreateCustomerRequest |
| CustomerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetAddressDataRequest, GetAddressesDataRequest, GetClientelingParametersDataRequest, GetCustomerDataRequest, GetCustomerGroupsDataRequest (+8) |
| CustomerGteSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll | Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCustomerTaxInformationDataRequest |
| CustomerInsightsService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Customers.dll |  |
| CustomerOrderDocumentOperationDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetCustomerOrderDocumentOperationDataRequest |
| CustomerOrderDocumentOperationSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | SaveCustomerOrderDocumentOperationDataRequest |
| CustomerOrderService | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | SaveCustomerOrderRealtimeRequest, RecallCustomerOrderRealtimeRequest, GetInvoiceRealtimeRequest, GetInvoiceDetailsRealtimeRequest, PickAndPackOrderRealtimeRequest (+10) |
| CustomerOrderValidationService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | ValidateCustomerOrderModeChangeRequest, ValidatePartiallyFulfilledOrderUpdateServiceRequest, ValidateCustomerOrderCartLineDeliveryDateRequest, ValidateCustomerOrderPickupTimeslotRequest |
| CustomerPaymentService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Payments.dll | CalculatePaymentAmountServiceRequest, AuthorizePaymentServiceRequest, VoidPaymentServiceRequest, GetChangePaymentServiceRequest, IsTenderLineLinkedRefundableServiceRequest |
| CustomerSearchAzureService | handler | Microsoft.Dynamics.Commerce.Runtime.SearchServices.Azure.dll |  |
| CustomerSearchRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | CustomersSearchRequest |
| CustomerService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Customers.dll | SaveCustomerServiceRequest, GetCustomersServiceRequest, CustomersSearchServiceRequest, GetCustomerGroupsServiceRequest, GetCustomerAffiliationsServiceRequest (+17) |
| CustomerSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | CreateOrUpdateCustomerDataRequest, CreateOrUpdateAsyncCustomerAddressDataRequest, GetSimpleCustomersDataRequest, GetCustomerAddressesDataRequest, GetCustomersDataRequest (+22) |
| CustomerTaxInformationDataService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll | GetCustomerTaxInformationDataRequest, GetPrimaryAddressTaxInformationDataRequest |
| CustomerTransactionServiceRequestHandler | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | GetCustomerBalanceRealtimeRequest, ValidateCustomerAccountPaymentRealtimeRequest, SearchCustomersRealtimeRequest, DownloadCustomerRealtimeRequest, DownloadPartyRealtimeRequest (+17) |
| CustomerTransactionServiceRequestHandlerAsync | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | SaveCustomerContactsRealtimeRequest |
| CustomerValidationService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | ValidateCnpjNumberRequest, ValidateCpfNumberRequest, ValidateForeignerIdRequest |
| CustomerValidationService | handler | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.dll | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Messages.ValidateCnpjNumberRequest, Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Messages.ValidateCpfNumberRequest, Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.Messages.ValidateForeignerIdRequest |
| FiscalCustomerAdditionalInfoDataService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll | SaveFiscalCustomerAdditionalInfoDataRequest, GetFiscalCustomerAdditionalInfoDataRequest |
| FiscalCustomerAdditionalInfoValidationService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | ValidateFiscalCustomerAdditionalInfoRequest |
| FiscalCustomerValidationService | handler | Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.dll | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Messages.Brazil.ValidateFiscalCustomerRequest, Microsoft.Dynamics.Commerce.Runtime.Localization.Services.Messages.Brazil.ValidateFiscalCustomerForCartCheckoutRequest, Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.Messages.ValidateFiscalCustomerRequest, Microsoft.Dynamics.Commerce.Runtime.ElectronicFiscalDocumentBrazil.Services.Messages.ValidateFiscalCustomerForCartCheckoutRequest |
| GetCustomerLoyaltyCardsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetCustomerLoyaltyCardsRequest |
| InitiateLinkToExistingCustomerRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | InitiateLinkToExistingCustomerRequest |
| PricingPropertyCustomerAttributeProvider | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll | ResolvePricingPropertyValuesServiceRequest |
| PricingPropertyCustomerProvider | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll | ResolvePricingPropertyValuesServiceRequest |
| RecallCustomerOrderRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | RecallCustomerOrderRequest |
| RefreshCustomerAffiliationsServiceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Customers.dll | RefreshCustomerAffiliationsServiceRequest |
| SaveCustomerOrderRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | SaveCustomerOrderRequest |
| SendCustomerEmailRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | SendCustomerEmailRequest |
| StaffManagedBusinessPartnerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetBusinessPartnersByStaffIdDataRequest, ValidateUserCanActOnBehalfOfCustomerDataRequest |
| TaxIdentifiersCustomerService | handler | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.dll | CustomerSearchByFieldsServiceRequest |
| TaxRegistrationIdCustomerService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | CustomerSearchByFieldsServiceRequest |
| TaxRegistrationIdCustomerService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | CustomerSearchByFieldsServiceRequest |
| TaxRegistrationIdCustomerService | handler | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.dll | CustomerSearchByFieldsServiceRequest |
| TaxRegistrationIdCustomerService | handler | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.dll | CustomerSearchByFieldsServiceRequest |
| TaxRegistrationIdFiscalCustomerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.Poland.GetFiscalCustomerDataDataRequest, Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.Poland.SaveFiscalCustomerDataDataRequest |
| TaxRegistrationIdFiscalCustomerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.Italy.GetFiscalCustomerDataDataRequest, Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.Italy.SaveFiscalCustomerDataDataRequest, GetCustomerFiscalCodeDataRequest, SaveCustomerFiscalCodeDataRequest, GetFiscalCustomerParametersDataRequest (+1) |
| TaxRegistrationIdFiscalCustomerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.dll | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.Italy.GetFiscalCustomerDataDataRequest, Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.Italy.SaveFiscalCustomerDataDataRequest, Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.Italy.GetCustomerFiscalCodeDataRequest, Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.Italy.SaveCustomerFiscalCodeDataRequest, Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.Messages.GetFiscalCustomerDataDataRequest (+3) |
| TaxRegistrationIdFiscalCustomerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.dll | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.Poland.GetFiscalCustomerDataDataRequest, Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.Poland.SaveFiscalCustomerDataDataRequest, Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.Messages.GetFiscalCustomerDataDataRequest, Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.Messages.SaveFiscalCustomerDataDataRequest |
| UpdateCustomerRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | UpdateCustomerRequest |
| ValidateCustomerDepositOverrideRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | ValidateCustomerDepositOverrideRequest |

## Triggers (20)

| Trigger | Assembly | Supported Requests |
|---------|----------|--------------------|
| CreateOrUpdateCustomerDataRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | CreateOrUpdateCustomerDataRequest |
| CustomerOrderServiceTriggers | Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll | SaveCustomerOrderRealtimeRequest, CreateOrderFromCartRequest, CreateSalesOrderServiceRequest, RecallCustomerOrderRealtimeRequest, GetInvoiceRealtimeRequest |
| CustomerOrderServiceTriggers | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | SaveCustomerOrderRealtimeRequest, CreateOrderFromCartRequest, CreateSalesOrderServiceRequest, RecallCustomerOrderRealtimeRequest, GetInvoiceRealtimeRequest |
| GetCustomersDataRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetCustomersDataRequest |
| GetCustomersServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetCustomersServiceRequest |
| GetCustomersServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetCustomersServiceRequest |
| GetCustomersServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | GetCustomersServiceRequest |
| GetCustomersServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.dll | GetCustomersServiceRequest |
| GetCustomersServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.dll | GetCustomersServiceRequest |
| GetCustomersServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.dll | GetCustomersServiceRequest |
| GetCustomersServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.dll | GetCustomersServiceRequest |
| SaveCustomerServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | SaveCustomerServiceRequest |
| SaveCustomerServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | SaveCustomerServiceRequest |
| SaveCustomerServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Localization.Services.dll | SaveCustomerServiceRequest |
| SaveCustomerServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.Services.Customers.dll | SaveCustomerServiceRequest |
| SaveCustomerServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdIndia.dll | SaveCustomerServiceRequest |
| SaveCustomerServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdItaly.dll | SaveCustomerServiceRequest |
| SaveCustomerServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdPoland.dll | SaveCustomerServiceRequest |
| SaveCustomersServiceRequestTrigger | Microsoft.Dynamics.Commerce.Runtime.TaxRegistrationIdBrazil.dll | SaveCustomerServiceRequest |
| ValidateBusinessPartnerCatalogTrigger | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | SaveProductListServiceRequest, ProductSearchRequest, GetProductComparisonServiceRequest, SearchProductsRequest, GetProductSearchSuggestionsRequest, GetProductSearchRefinersRequest, GetProductSearchRefinerValuesRequest, GetProductAttributeValuesServiceRequest, GetProductRelationTypesDataRequest, GetRelatedProductsRequest, GetProductRefinersRequest, GetActiveProductPriceRequest, GetProductMediaLocationsDataRequest, SearchMediaLocationsDataRequest, GetProductMediaBlobsDataRequest, GetApplicableWarrantiesRequest, GetCategoryPathsServiceRequest, AddCartLinesRequest, UpdateCartLinesRequest, GetCategoryHierarchyServiceRequest, GetProductsServiceRequest, GetDimensionValuesWithEstimatedAvailabilitiesServiceRequest |
