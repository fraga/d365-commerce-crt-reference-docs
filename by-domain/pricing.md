# Pricing

## Handlers (38)

| Handler | Kind | Assembly | Supported Requests |
|---------|------|----------|--------------------|
| AddChargeRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | AddChargeRequest |
| AddOrRemoveDiscountCodesRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | AddOrRemoveDiscountCodesRequest |
| AttributePricingService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll | ResolveHierarchicalPricingAttributeServiceRequest, GetMatchingChargeConfigurationsByPricingAttributesServiceRequest |
| AttributePricingSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll |  |
| AvailablePromotionsService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll | GetAvailablePromotionsServiceRequest, RemoveNotApplicablePromotionsServiceRequest |
| ChargeDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetChargeConfigurationsDataRequest, GetChargeLinesDataRequest, GetChargeConfigurationsByHeaderDataRequest, GetSalesParametersDataRequest, GetChargeCodesDataRequest |
| ChargeService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll | GetChargesServiceRequest, GetAdvancedChargesServiceRequest, DefineAdvancedAutoChargesServiceRequest, DefineAttributePricingAutoChargesServiceRequest, CalculateAdvancedChargesServiceRequest (+5) |
| ChargeSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetAutoChargesApplicabilityRequest, GetPreviouslyRefundedChargeAmountDataRequest, GetTransactionChageLinesDataRequest |
| ChargeSqlSharedDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | LogChargeOverridesDataRequest, InsertMarkupTransDataRequest |
| CouponDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetCouponCodesDataRequest, GetCouponCodesByOfferIdsDataRequest, GetAvailablePromotionCouponCodesDataRequest |
| CouponService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll | UpdateCouponCodesOnCartServiceRequest, ValidateCouponCodesServiceRequest, UpdateCouponUsageServiceRequest, ValidateCouponUsageInOrderServiceRequest |
| CouponSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | ValidateCouponUsageLimitsDataRequest, UpdateCouponUsageDataRequest |
| CouponTransactionServiceRequestHandler | handler | Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll | ValidateCouponUsageLimitsRealtimeRequest, UpdateCouponUsageRealtimeRequest |
| GetActiveProductPriceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetActiveProductPriceRequest |
| GetAvailablePromotionsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetAvailablePromotionsRequest |
| GetDiscountCodesRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetDiscountCodesRequest |
| GetIndependentProductPriceDiscountRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetIndependentProductPriceDiscountRequest |
| GetPriceValidationConfigurationRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetPriceValidationConfigurationRequest |
| GetProductPriceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetProductPriceRequest |
| GetPromotionsRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | GetPromotionsRequest |
| IndiaMaxRetailPriceDataService | handler | Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.India.GetIndiaMaxRetailPriceFromTradeAgreementsDataRequest, Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetIndiaMaxRetailPriceFromTradeAgreementsDataRequest, Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemsMaxRetailPricesDataRequest |
| IndiaMaxRetailPriceDataService | handler | Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll | GetIndiaMaxRetailPriceFromTradeAgreementsDataRequest, GetItemsMaxRetailPricesDataRequest |
| OverrideChargeRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | OverrideChargeRequest |
| PriceCheckRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | PriceCheckRequest |
| PricingDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetDiscountCodesDataRequest, GetCustomerPriceGroupDataRequest, GetPricingPropertyDefinitionsDataRequest |
| PricingPropertyAffiliationProvider | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll | ResolvePricingPropertyValuesServiceRequest |
| PricingPropertyChannelIdProvider | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll | ResolvePricingPropertyValuesServiceRequest |
| PricingPropertyLoyaltyProvider | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll | ResolvePricingPropertyValuesServiceRequest |
| PricingPropertyProductAttributeProvider | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll | ResolvePricingPropertyValuesServiceRequest |
| PricingPropertyProductProvider | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll | ResolvePricingPropertyValuesServiceRequest |
| PricingPropertySalesLineAttributeProvider | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll | ResolvePricingPropertyValuesServiceRequest |
| PricingPropertySalesLineProvider | single_handler | Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll | ResolvePricingPropertyValuesServiceRequest |
| PricingService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll | CalculatePricesServiceRequest, CalculateDiscountsServiceRequest, ValidateDiscountsServiceRequest, GetAllPeriodicDiscountsServiceRequest, GetDiscountCodesServiceRequest (+5) |
| PricingSqlDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.dll | GetAllRetailDiscountPriceGroupsDataRequest, GetPriceGroupByChannelIdDataRequest, GetPriceGroupByGroupIdDataRequest, GetRetailDiscountPriceGroupByOfferIdsDataRequest, GetChannelPriceConfigurationDataRequest (+3) |
| PricingSqlServerDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetPriceAdjustmentsDataRequest, GetRetailChannelDiscountsDataRequest, GetSalesAgreementsByCustomerDataRequest, GetSalesAgreementsByRecordIdDataRequest, ReadDiscountTradeAgreementsBySearchCriteriaDataRequest (+6) |
| PricingSqlSharedDataService | handler | Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll | GetNotApplicableMatchAllPriceGroupDiscountsDataRequest, GetItemsPriceDataRequest, GetDiscountsByCategoriesDataRequest, GetDiscountsByProductsDataRequest, GetDiscountsByProductMastersDataRequest (+5) |
| ProductPricingService | handler | Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll | GetProductPricesServiceRequest |
| SetInvoiceLinePriceRequestHandler | single_handler | Microsoft.Dynamics.Commerce.Runtime.Workflow.dll | SetInvoiceLinePriceRequest |
