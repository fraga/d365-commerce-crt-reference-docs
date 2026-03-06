# Pricing

## Handlers (44)

| Handler | Kind | Supported Requests |
|---------|------|--------------------|
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.ChargeSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.ChargeSqlSharedDataService.md) | handler | [LogChargeOverridesDataRequest](../by-request-type/LogChargeOverridesDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ChargeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ChargeDataService.md) | handler | [GetChargeConfigurationsDataRequest](../by-request-type/GetChargeConfigurationsDataRequest.md), [GetChargeLinesDataRequest](../by-request-type/GetChargeLinesDataRequest.md), [GetChargeConfigurationsByHeaderDataRequest](../by-request-type/GetChargeConfigurationsByHeaderDataRequest.md), [GetSalesParametersDataRequest](../by-request-type/GetSalesParametersDataRequest.md), [GetChargeCodesDataRequest](../by-request-type/GetChargeCodesDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.CouponDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.CouponDataService.md) | handler | [GetCouponCodesDataRequest](../by-request-type/GetCouponCodesDataRequest.md), [GetCouponCodesByOfferIdsDataRequest](../by-request-type/GetCouponCodesByOfferIdsDataRequest.md), [GetAvailablePromotionCouponCodesDataRequest](../by-request-type/GetAvailablePromotionCouponCodesDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.CouponSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.CouponSqlServerDataService.md) | handler | [ValidateCouponUsageLimitsDataRequest](../by-request-type/ValidateCouponUsageLimitsDataRequest.md), [UpdateCouponUsageDataRequest](../by-request-type/UpdateCouponUsageDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.PricingDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.PricingDataService.md) | handler | [GetDiscountCodesDataRequest](../by-request-type/GetDiscountCodesDataRequest.md), [GetCustomerPriceGroupDataRequest](../by-request-type/GetCustomerPriceGroupDataRequest.md), [GetPricingPropertyDefinitionsDataRequest](../by-request-type/GetPricingPropertyDefinitionsDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.PricingSqlDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.PricingSqlDataService.md) | handler | [GetAllRetailDiscountPriceGroupsDataRequest](../by-request-type/GetAllRetailDiscountPriceGroupsDataRequest.md), [GetPriceGroupByChannelIdDataRequest](../by-request-type/GetPriceGroupByChannelIdDataRequest.md), [GetPriceGroupByGroupIdDataRequest](../by-request-type/GetPriceGroupByGroupIdDataRequest.md), [GetRetailDiscountPriceGroupByOfferIdsDataRequest](../by-request-type/GetRetailDiscountPriceGroupByOfferIdsDataRequest.md), [GetChannelPriceConfigurationDataRequest](../by-request-type/GetChannelPriceConfigurationDataRequest.md) (+3) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.PricingSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.PricingSqlSharedDataService.md) | handler | [GetNotApplicableMatchAllPriceGroupDiscountsDataRequest](../by-request-type/GetNotApplicableMatchAllPriceGroupDiscountsDataRequest.md), [GetItemsPriceDataRequest](../by-request-type/GetItemsPriceDataRequest.md), [GetDiscountsByCategoriesDataRequest](../by-request-type/GetDiscountsByCategoriesDataRequest.md), [GetDiscountsByProductMastersDataRequest](../by-request-type/GetDiscountsByProductMastersDataRequest.md), [GetPriceGroupsByPropertiesDataRequest](../by-request-type/GetPriceGroupsByPropertiesDataRequest.md) (+8) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AttributePricingSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AttributePricingSqlServerDataService.md) | handler |  |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ChargeSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ChargeSqlServerDataService.md) | handler | [GetAutoChargesApplicabilityRequest](../by-request-type/GetAutoChargesApplicabilityRequest.md), [GetPreviouslyRefundedChargeAmountDataRequest](../by-request-type/GetPreviouslyRefundedChargeAmountDataRequest.md), [GetTransactionChageLinesDataRequest](../by-request-type/GetTransactionChageLinesDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PricingSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PricingSqlServerDataService.md) | handler | [GetPriceAdjustmentsDataRequest](../by-request-type/GetPriceAdjustmentsDataRequest.md), [GetRetailChannelDiscountsDataRequest](../by-request-type/GetRetailChannelDiscountsDataRequest.md), [GetSalesAgreementsByCustomerDataRequest](../by-request-type/GetSalesAgreementsByCustomerDataRequest.md), [GetSalesAgreementsByRecordIdDataRequest](../by-request-type/GetSalesAgreementsByRecordIdDataRequest.md), [ReadDiscountTradeAgreementsBySearchCriteriaDataRequest](../by-request-type/ReadDiscountTradeAgreementsBySearchCriteriaDataRequest.md) (+12) |
| [Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.IndiaMaxRetailPriceDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.IndiaMaxRetailPriceDataService.md) | handler | [GetIndiaMaxRetailPriceFromTradeAgreementsDataRequest](../by-request-type/GetIndiaMaxRetailPriceFromTradeAgreementsDataRequest.md), [GetItemsMaxRetailPricesDataRequest](../by-request-type/GetItemsMaxRetailPricesDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.IndiaMaxRetailPriceDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.IndiaMaxRetailPriceDataService.md) | handler | [GetIndiaMaxRetailPriceFromTradeAgreementsDataRequest](../by-request-type/GetIndiaMaxRetailPriceFromTradeAgreementsDataRequest.md), [GetItemsMaxRetailPricesDataRequest](../by-request-type/GetItemsMaxRetailPricesDataRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.AttributePricingService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.AttributePricingService.md) | handler | [ResolveHierarchicalPricingAttributeServiceRequest](../by-request-type/ResolveHierarchicalPricingAttributeServiceRequest.md), [GetMatchingChargeConfigurationsByPricingAttributesServiceRequest](../by-request-type/GetMatchingChargeConfigurationsByPricingAttributesServiceRequest.md), [GetSalesTransactionHashesForChargeCalculationRequest](../by-request-type/GetSalesTransactionHashesForChargeCalculationRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.AvailablePromotionsService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.AvailablePromotionsService.md) | handler | [GetAvailablePromotionsServiceRequest](../by-request-type/GetAvailablePromotionsServiceRequest.md), [RemoveNotApplicablePromotionsServiceRequest](../by-request-type/RemoveNotApplicablePromotionsServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.ChargeService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.ChargeService.md) | handler | [GetChargesServiceRequest](../by-request-type/GetChargesServiceRequest.md), [GetAdvancedChargesServiceRequest](../by-request-type/GetAdvancedChargesServiceRequest.md), [DefineAdvancedAutoChargesServiceRequest](../by-request-type/DefineAdvancedAutoChargesServiceRequest.md), [DefineAttributePricingAutoChargesServiceRequest](../by-request-type/DefineAttributePricingAutoChargesServiceRequest.md), [CalculateAdvancedChargesServiceRequest](../by-request-type/CalculateAdvancedChargesServiceRequest.md) (+5) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.CouponService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.CouponService.md) | handler | [UpdateCouponCodesOnCartServiceRequest](../by-request-type/UpdateCouponCodesOnCartServiceRequest.md), [ValidateCouponCodesServiceRequest](../by-request-type/ValidateCouponCodesServiceRequest.md), [UpdateCouponUsageServiceRequest](../by-request-type/UpdateCouponUsageServiceRequest.md), [ValidateCouponUsageInOrderServiceRequest](../by-request-type/ValidateCouponUsageInOrderServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeChannelProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeChannelProvider.md) | single_handler | [ResolvePriceAttributeValuesServiceRequest](../by-request-type/ResolvePriceAttributeValuesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeProductAttributeProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeProductAttributeProvider.md) | single_handler | [ResolvePriceAttributeValuesServiceRequest](../by-request-type/ResolvePriceAttributeValuesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeProductProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeProductProvider.md) | single_handler | [ResolvePriceAttributeValuesServiceRequest](../by-request-type/ResolvePriceAttributeValuesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeSalesLineAttributeProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeSalesLineAttributeProvider.md) | single_handler | [ResolvePriceAttributeValuesServiceRequest](../by-request-type/ResolvePriceAttributeValuesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeSalesLineProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeSalesLineProvider.md) | single_handler | [ResolvePriceAttributeValuesServiceRequest](../by-request-type/ResolvePriceAttributeValuesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertyAffiliationProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertyAffiliationProvider.md) | single_handler | [ResolvePricingPropertyValuesServiceRequest](../by-request-type/ResolvePricingPropertyValuesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertyChannelIdProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertyChannelIdProvider.md) | single_handler | [ResolvePricingPropertyValuesServiceRequest](../by-request-type/ResolvePricingPropertyValuesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertyLoyaltyProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertyLoyaltyProvider.md) | single_handler | [ResolvePricingPropertyValuesServiceRequest](../by-request-type/ResolvePricingPropertyValuesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertyProductAttributeProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertyProductAttributeProvider.md) | single_handler | [ResolvePricingPropertyValuesServiceRequest](../by-request-type/ResolvePricingPropertyValuesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertyProductProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertyProductProvider.md) | single_handler | [ResolvePricingPropertyValuesServiceRequest](../by-request-type/ResolvePricingPropertyValuesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertySalesLineAttributeProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertySalesLineAttributeProvider.md) | single_handler | [ResolvePricingPropertyValuesServiceRequest](../by-request-type/ResolvePricingPropertyValuesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertySalesLineProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertySalesLineProvider.md) | single_handler | [ResolvePricingPropertyValuesServiceRequest](../by-request-type/ResolvePricingPropertyValuesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.PricingService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.PricingService.md) | handler | [CalculatePricesServiceRequest](../by-request-type/CalculatePricesServiceRequest.md), [CalculateDiscountsServiceRequest](../by-request-type/CalculateDiscountsServiceRequest.md), [ValidateDiscountsServiceRequest](../by-request-type/ValidateDiscountsServiceRequest.md), [GetAllPeriodicDiscountsServiceRequest](../by-request-type/GetAllPeriodicDiscountsServiceRequest.md), [GetDiscountCodesServiceRequest](../by-request-type/GetDiscountCodesServiceRequest.md) (+6) |
| [Microsoft.Dynamics.Commerce.Runtime.Services.ProductPricingService (Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Services.ProductPricingService.md) | handler | [GetProductPricesServiceRequest](../by-request-type/GetProductPricesServiceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.TransactionService.CouponTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.TransactionService.CouponTransactionServiceRequestHandler.md) | handler | [ValidateCouponUsageLimitsRealtimeRequest](../by-request-type/ValidateCouponUsageLimitsRealtimeRequest.md), [UpdateCouponUsageRealtimeRequest](../by-request-type/UpdateCouponUsageRealtimeRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.AddChargeRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.AddChargeRequestHandler.md) | single_handler | [AddChargeRequest](../by-request-type/AddChargeRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.AddOrRemoveDiscountCodesRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.AddOrRemoveDiscountCodesRequestHandler.md) | single_handler | [AddOrRemoveDiscountCodesRequest](../by-request-type/AddOrRemoveDiscountCodesRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetActiveProductPriceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetActiveProductPriceRequestHandler.md) | single_handler | [GetActiveProductPriceRequest](../by-request-type/GetActiveProductPriceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAvailablePromotionsRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAvailablePromotionsRequestHandler.md) | single_handler | [GetAvailablePromotionsRequest](../by-request-type/GetAvailablePromotionsRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDiscountCodesRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDiscountCodesRequestHandler.md) | single_handler | [GetDiscountCodesRequest](../by-request-type/GetDiscountCodesRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetIndependentProductPriceDiscountRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetIndependentProductPriceDiscountRequestHandler.md) | single_handler | [GetIndependentProductPriceDiscountRequest](../by-request-type/GetIndependentProductPriceDiscountRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetPriceValidationConfigurationRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetPriceValidationConfigurationRequestHandler.md) | single_handler | [GetPriceValidationConfigurationRequest](../by-request-type/GetPriceValidationConfigurationRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetProductPriceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetProductPriceRequestHandler.md) | single_handler | [GetProductPriceRequest](../by-request-type/GetProductPriceRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetProductPromotionsRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetProductPromotionsRequestHandler.md) | single_handler | [GetProductPromotionsRequest](../by-request-type/GetProductPromotionsRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetPromotionsRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetPromotionsRequestHandler.md) | single_handler | [GetPromotionsRequest](../by-request-type/GetPromotionsRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.OverrideChargeRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.OverrideChargeRequestHandler.md) | single_handler | [OverrideChargeRequest](../by-request-type/OverrideChargeRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.PriceCheckRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.PriceCheckRequestHandler.md) | single_handler | [PriceCheckRequest](../by-request-type/PriceCheckRequest.md) |
| [Microsoft.Dynamics.Commerce.Runtime.Workflow.SetInvoiceLinePriceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.SetInvoiceLinePriceRequestHandler.md) | single_handler | [SetInvoiceLinePriceRequest](../by-request-type/SetInvoiceLinePriceRequest.md) |

## Request Types (92)

### AddChargeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.AddChargeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.AddChargeRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |
| `ChargeModule` | ModuleType |
| `string` | ChargeCode |
| `decimal` | Amount |

### AddOrRemoveDiscountCodesRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.AddOrRemoveDiscountCodesRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.AddOrRemoveDiscountCodesRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |
| `ReadOnlyCollection<string>` | DiscountCodes |
| `DiscountCodesOperation` | DiscountCodesOperation |

### CalculateAdvancedChargesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateAdvancedChargesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ChargeService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### CalculateChargeAmountToRefundServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateChargeAmountToRefundServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ChargeService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `decimal` | RemainChargeAmount |
| `decimal` | RemainQuantity |
| `decimal` | ReturnQuantity |
| `ChargeMethod` | ChargeMethod |
| `bool` | IsHeaderChargeProrated |

### CalculateDiscountsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateDiscountsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PricingService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `DiscountCalculationMode` | DiscountCalculationMode |
| `bool` | CalculateSimpleDiscountOnly |
| `DateTimeOffset?` | DateWhenActive |

### CalculatePricesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculatePricesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PricingService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `PricingCalculationMode` | PricingCalculationMode |
| `DateTimeOffset?` | DateWhenActive |
| `bool` | IncludeAttainablePricesAndDiscounts |

### CalculateQuantityFromPriceServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateQuantityFromPriceServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.BarcodeService (Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `decimal` | DefaultProductPrice |
| `decimal` | BarcodePrice |
| `string` | UnitOfMeasure |

### CalculateShippingDiscountsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateShippingDiscountsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PricingService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `DateTimeOffset?` | DateWhenActive |

### CreateChargeLineOverrideServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateChargeLineOverrideServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ChargeService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `ChargeLine` | Charge |
| `string` | OverrideReason |
| `decimal` | OriginalAmount |

### DefineAdvancedAutoChargesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DefineAdvancedAutoChargesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ChargeService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### DefineAttributePricingAutoChargesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DefineAttributePricingAutoChargesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ChargeService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### FilterOutAlreadyRefundedChargeLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.FilterOutAlreadyRefundedChargeLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ChargeService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<ChargeLine>` | ChargeLines |
| `SalesTransaction` | OriginalTransaction |
| `decimal` | SalesLineNum |

### FilterOutNonRefundableChargeLinesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.FilterOutNonRefundableChargeLinesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ChargeService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<ChargeLine>` | ChargeLines |

### GetActiveProductPriceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetActiveProductPriceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetActiveProductPriceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Triggers:** Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidateBusinessPartnerCatalogTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `IEnumerable<long>` | ProductIds |
| `string` | CustomerAccountNumber |
| `DateTimeOffset` | DateWhenActive |
| `ProjectionDomain` | Context |
| `IEnumerable<AffiliationLoyaltyTier>` | AffiliationLoyaltyTiers |
| `bool` | IncludeSimpleDiscountsInContextualPrice |
| `bool` | IncludeVariantPriceRange |
| `bool` | IncludeAttainablePricesAndDiscounts |
| `PriceLookupContext` | PriceLookupContext |

### GetAdvancedChargesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAdvancedChargesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ChargeService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### GetAllPeriodicDiscountsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAllPeriodicDiscountsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PricingService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### GetAutoChargesApplicabilityRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAutoChargesApplicabilityRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ChargeSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ChargeChannelType` | ChannelType |
| `string` | ChannelRelation |
| `long` | ChannelId |

### GetAvailablePromotionCouponCodesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAvailablePromotionCouponCodesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.CouponDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | DiscountOfferIds |

### GetAvailablePromotionsRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetAvailablePromotionsRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAvailablePromotionsRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |
| `IEnumerable<string>` | CartLineIds |

### GetAvailablePromotionsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAvailablePromotionsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.AvailablePromotionsService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `ICollection<string>` | SalesLineIds |

### GetBasePriceForTaxIncludedServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetBasePriceForTaxIncludedServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Localization.TaxServiceBrazil.TaxServiceBrazilRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TaxServiceBrazil.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `TaxCode` | TaxCode |
| `ReadOnlyCollection<TaxCode>` | TaxCodes |
| `TaxableItem` | TaxableEntity |
| `ReadOnlyCollection<SalesLine>` | ActiveSalesLines |
| `decimal` | IntervalBasis |
| `bool` | CalculateBasePrice |
| `bool` | TaxInStoreCurrency |
| `bool` | TaxIncludedInPrice |
| `bool` | IsTaxExemptedForPriceInclusive |

### GetChargeCodesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChargeCodesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ChargeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ChargeModule` | ModuleType |

### GetChargeConfigurationsByHeaderDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChargeConfigurationsByHeaderDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ChargeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ChargeLevel` | ChargeType |
| `ChargeConfigurationHeader` | Header |

### GetChargeLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChargeLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.ChargeDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | ChargeCode |
| `ChargeModule` | ChargeModule |

### GetChargeTaxLinesGTEDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChargeTaxLinesGTEDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TransactionId |
| `decimal` | SalesLineNumber |
| `decimal` | MarkupLineNumber |

### GetChargeTaxLinesGteDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.India.GetChargeTaxLinesGteDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TransactionId |
| `decimal` | SalesLineNumber |
| `decimal` | MarkupLineNumber |

### GetChargesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChargesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ChargeService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### GetCouponCodesByOfferIdsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCouponCodesByOfferIdsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.CouponDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | DiscountOfferIds |

### GetCouponCodesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCouponCodesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.CouponDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | CouponCodes |
| `string` | DiscountOfferId |

### GetDiscountCodesRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetDiscountCodesRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetDiscountCodesRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | OfferId |
| `string` | DiscountCode |
| `string` | Keyword |
| `DateTimeOffset` | ActiveDate |

### GetDiscountCodesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDiscountCodesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PricingService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | OfferId |
| `string` | DiscountCode |
| `string` | Keyword |
| `DateTimeOffset` | ActiveDate |

### GetDiscountFiscalTextByOfferIdDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDiscountFiscalTextByOfferIdDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.FiscalTextSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ReadOnlyCollection<string>` | OfferIds |
| `string` | FunctionalityProfileGroupId |

### GetDiscountFiscalTextDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDiscountFiscalTextDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.FiscalTextSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | FunctionalityProfileGroupId |

### GetDiscountLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDiscountLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.SalesTransactionDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `DiscountLinesQueryCriteria` | Criteria |

### GetDiscountsByCategoriesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDiscountsByCategoriesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.PricingSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** GetDiscountsDataRequest

| Type | Property |
|------|----------|
| `IEnumerable<long>` | CatagoryIds |
| `IEnumerable<long>` | CategoryIds |

### GetDiscountsByProductMastersDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDiscountsByProductMastersDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.PricingSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** GetDiscountsDataRequest

| Type | Property |
|------|----------|
| `IEnumerable<long>` | ProductIds |

### GetDiscountsByProductsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDiscountsByProductsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PricingSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** GetDiscountsDataRequest

| Type | Property |
|------|----------|
| `IEnumerable<long>` | ProductIds |

### GetDiscountsForPriceGroupsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDiscountsForPriceGroupsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.PricingSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<PeriodicDiscount>` | Discounts |
| `IEnumerable<PriceGroup>` | PriceGroups |

### GetIndependentPriceDiscountServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetIndependentPriceDiscountServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PricingService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `bool` | CalculateForNewSalesLinesOnly |
| `HashSet<string>` | NewSalesLineIdSet |
| `DateTimeOffset?` | DateWhenActive |
| `bool` | IncludeAttainablePricesAndDiscounts |

### GetIndependentProductPriceDiscountRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetIndependentProductPriceDiscountRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetIndependentProductPriceDiscountRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `IEnumerable<long>` | ProductIds |
| `string` | CustomerAccountNumber |
| `ProjectionDomain` | Context |
| `IEnumerable<AffiliationLoyaltyTier>` | AffiliationLoyaltyTiers |

### GetIndiaMaxRetailPriceFromTradeAgreementsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetIndiaMaxRetailPriceFromTradeAgreementsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.IndiaMaxRetailPriceDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.IndiaMaxRetailPriceDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<long>` | TradeAgreementRecordIds |

### GetItemsMaxRetailPricesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemsMaxRetailPricesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.IndiaMaxRetailPriceDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.IndiaMaxRetailPriceDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ICollection<string>` | ItemIds |

### GetItemsPriceDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemsPriceDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.PricingSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | ItemIds |

### GetMatchingChargeConfigurationsByPricingAttributesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetMatchingChargeConfigurationsByPricingAttributesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.AttributePricingService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<ChargeConfiguration>` | AttributePricingChargeConfigurations |
| `SimpleCustomer` | SimpleCustomer |
| `SalesTransaction` | Transaction |

### GetNotApplicableMatchAllPriceGroupDiscountsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetNotApplicableMatchAllPriceGroupDiscountsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.PricingSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | OfferIds |
| `ISet<string>` | PriceGroups |

### GetPreviouslyRefundedChargeAmountDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPreviouslyRefundedChargeAmountDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ChargeSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | TransactionId |
| `string` | TerminalId |
| `string` | StoreId |
| `decimal` | SalesLineNumber |

### GetPriceAdjustmentsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAdjustmentsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PricingSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<ItemUnit>` | Items |
| `ISet<string>` | PriceGroups |
| `DateTimeOffset` | StartDate |
| `DateTimeOffset` | EndDate |

### GetPriceAttributeDefinitionsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAttributeDefinitionsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.PricingSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<PriceComponentCode>` | PriceComponentCodes |

### GetPriceGroupByAffiliationLoyaltyTiersDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceGroupByAffiliationLoyaltyTiersDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.PricingSqlDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<AffiliationLoyaltyTier>` | AffiliationLoyaltyTiers |

### GetPriceGroupByChannelIdDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceGroupByChannelIdDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.PricingSqlDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | ChannelId |

### GetPriceGroupByGroupIdDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceGroupByGroupIdDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.PricingSqlDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | GroupId |

### GetPriceGroupsByPriceAttributesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceGroupsByPriceAttributesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.PricingSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `PriceAttributeValueContext` | PriceAttributeValueContext |

### GetPriceGroupsByPriceLookupContextServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPriceGroupsByPriceLookupContextServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PricingService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `PriceLookupContext` | PriceLookupContext |

### GetPriceLinesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceLinesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.SalesTransactionDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `PriceLinesQueryCriteria` | Criteria |

### GetPriceParametersDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceParametersDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.PricingSqlDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ColumnSet` | ColumnSet |

### GetPricingRuleApplicabilitiesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPricingRuleApplicabilitiesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.PricingSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `PriceAttributeValueContext` | PriceAttributeValueContext |
| `IEnumerable<PriceGroup>` | PriceGroups |
| `DateTimeOffset` | ActiveDate |

### GetProductDiscountDetailDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductDiscountDetailDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PricingSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | ProductDiscountIds |

### GetProductDiscountIdsByPriceGroupsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductDiscountIdsByPriceGroupsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PricingSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | ProductDiscountIds |
| `IEnumerable<PriceGroup>` | PriceGroups |
| `DateTimeOffset` | ActiveDate |

### GetProductPriceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductPriceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetProductPriceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `long` | ProductId |
| `string` | CustomerAccountNumber |
| `string` | UnitOfMeasureSymbol |
| `string` | LoyaltyCardId |
| `IEnumerable<AffiliationLoyaltyTier>` | AffiliationLoyaltyTiers |

### GetProductPricesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductPricesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ProductPricingService (Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<Product>` | Products |

### GetProductPromotionsRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductPromotionsRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetProductPromotionsRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `IEnumerable<string>` | ProductDiscountIds |
| `PriceLookupContext` | PriceLookupContext |
| `DateTimeOffset?` | ActiveDate |

### GetProductsWithDiscountByProductDiscountIdsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductsWithDiscountByProductDiscountIdsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PricingSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | ProductDisocuntIds |
| `long?` | ChannelId |
| `DateTimeOffset?` | ActiveDate |

### GetPromotionsRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetPromotionsRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.GetPromotionsRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |
| `string` | CustomerAccountNumber |

### GetRetailChannelDiscountsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetRetailChannelDiscountsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PricingSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `DiscountsSearchCriteria` | SearchCriteria |

### GetRetailDiscountPriceGroupByOfferIdsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetRetailDiscountPriceGroupByOfferIdsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.PricingSqlDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `ISet<string>` | OfferIds |

### GetRetailDiscountsByPropertiesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetRetailDiscountsByPropertiesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.PricingSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `PricingPropertyValueContext` | PropertyValueContext |
| `IEnumerable<PriceGroup>` | PriceGroups |
| `DateTimeOffset` | ActiveDate |
| `ICollection<ExtensiblePeriodicDiscountOfferType>` | DiscountOfferTypes |

### GetRetailPriceAdjustmentsByPropertiesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetRetailPriceAdjustmentsByPropertiesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.PricingSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `PricingPropertyValueContext` | PropertyValueContext |
| `IEnumerable<PriceGroup>` | PriceGroups |
| `DateTimeOffset` | ActiveDate |

### GetRetailShippingDiscountsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetRetailShippingDiscountsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PricingSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | DeliveryMode |
| `IEnumerable<ItemUnit>` | Items |
| `ISet<string>` | PriceGroups |
| `DateTimeOffset` | StartDate |
| `DateTimeOffset` | EndDate |
| `string` | CurrencyCode |

### GetTransactionChargeLinesTaxExemptPercentageServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTransactionChargeLinesTaxExemptPercentageServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.TaxService (Microsoft.Dynamics.Commerce.Runtime.Services.Taxes.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |

### InsertChargeTaxMeasureTableDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertChargeTaxMeasureTableDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<ChargeTaxMeasure>` | ChargeTaxMeasures |

### InsertChargeTaxTransGteTableDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertChargeTaxTransGteTableDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | SalesTransaction |

### LogChargeOverridesDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.LogChargeOverridesDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.ChargeSqlSharedDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<ChargeLine>` | ChargeLines |
| `string` | SalesOrderId |
| `string` | TransactionId |
| `long` | ChannelId |
| `string` | StoreNumber |
| `string` | TerminalId |

### OverrideChargeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.OverrideChargeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.OverrideChargeRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |
| `string` | ChargeLineId |
| `decimal` | Amount |
| `IEnumerable<ReasonCodeLine>` | ReasonCodeLines |

### PriceCheckRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.PriceCheckRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.PriceCheckRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | ItemId |
| `string` | InventoryDimensionId |
| `string` | UnitOfMeasureSymbol |
| `string` | CustomerAccountNumber |
| `decimal` | Quantity |
| `string` | Barcode |
| `long` | CatalogId |
| `string` | LoyaltyCardId |
| `IEnumerable<AffiliationLoyaltyTier>` | AffiliationLoyaltyTiers |

### ReadDiscountTradeAgreementsBySearchCriteriaDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReadDiscountTradeAgreementsBySearchCriteriaDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PricingSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** GetPriceAndDiscountDataRequest

| Type | Property |
|------|----------|
| `ISet<TradeAgreementSearchCriteria>` | TradeAgreementSearchCriteria |

### ReadPriceTradeAgreementsBySearchCriteriaDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReadPriceTradeAgreementsBySearchCriteriaDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PricingSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** GetPriceAndDiscountDataRequest

| Type | Property |
|------|----------|
| `ISet<TradeAgreementSearchCriteria>` | TradeAgreementSearchCriteria |

### ReadRetailShippingDiscountsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReadRetailShippingDiscountsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.PricingSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** GetPriceAndDiscountDataRequest

| Type | Property |
|------|----------|
| `string` | DeliveryMode |

### RemoveNotApplicablePromotionsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.RemoveNotApplicablePromotionsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.AvailablePromotionsService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `SalesTransaction` | AllDiscountsTransaction |

### ResetAllChargesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ResetAllChargesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.ChargeService (Microsoft.Dynamics.Commerce.Runtime.Services.Orders.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `string` | CartId |

### ResolveHierarchicalPricingAttributeServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ResolveHierarchicalPricingAttributeServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.AttributePricingService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IDictionary<IPricingAttribute, object>` | PricingProperties |

### ResolvePriceAttributeValuesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ResolvePriceAttributeValuesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeChannelProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeCustomerAttributeProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeCustomerProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeProductAttributeProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeProductProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeSalesLineAttributeProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeSalesLineProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeSalesOrderAttributeProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PriceAttributeSalesOrderProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<PriceAttributeDefinition>` | PriceAttributes |
| `SalesTransaction` | Transaction |

### ResolvePricingPropertyValuesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ResolvePricingPropertyValuesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertyAffiliationProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertyChannelIdProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertyCustomerAttributeProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertyCustomerProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertyLoyaltyProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertyProductAttributeProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertyProductProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertySalesLineAttributeProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertySalesLineProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll), Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.PricingPropertySalesOrderAttributeProvider (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<PricingPropertyDefinition>` | PricingProperties |
| `SalesTransaction` | Transaction |

### SetInvoiceLinePriceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.SetInvoiceLinePriceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Workflow.SetInvoiceLinePriceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)
**Inherits:** Request

| Type | Property |
|------|----------|
| `string` | CartId |
| `long?` | CartVersion |
| `string` | LineId |
| `decimal` | NewPrice |

### UpdateCouponUsageDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UpdateCouponUsageDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.CouponSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | CouponCodeIds |
| `string` | CustomerAccount |
| `long` | ChannelId |
| `string` | TransactionId |
| `string` | ReceiptId |
| `string` | SalesId |
| `CouponUsageStatus` | Status |
| `bool` | IsValidationRequired |

### UpdateCouponUsageRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.UpdateCouponUsageRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.CouponTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | CouponCodeIds |
| `string` | CustomerAccount |
| `long` | ChannelId |
| `string` | TransactionId |
| `string` | ReceiptId |
| `string` | SalesId |
| `CouponUsageStatus` | Status |
| `bool` | IsValidationRequired |

### UpdateCouponUsageServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateCouponUsageServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CouponService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `bool` | IsValidationRequired |

### UpdateMiscellaneousChargeTaxInformationDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UpdateMiscellaneousChargeTaxInformationDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.SqlServer.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.GenericTaxEngine.dll), Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.India.TaxTransGteSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.Localization.Data.Services.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `string` | StoreId |
| `string` | TerminalId |
| `string` | TransactionId |
| `string` | DataAreaId |
| `IEnumerable<SalesLine>` | SalesLines |

### ValidateCouponCodesServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateCouponCodesServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.CouponService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `IEnumerable<RetailCouponCode>` | CouponCodes |
| `SalesTransaction` | Transaction |
| `RetailCouponCode` | ExistingExclusiveCoupon |
| `IEnumerable<string>` | NewCouponCodeStrings |

### ValidateCouponUsageLimitsDataRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateCouponUsageLimitsDataRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.CouponSqlServerDataService (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)
**Inherits:** DataRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | CouponCodeIds |
| `string` | CustomerAccount |
| `long` | ChannelId |
| `string` | TransactionId |
| `string` | SalesId |

### ValidateCouponUsageLimitsRealtimeRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.ValidateCouponUsageLimitsRealtimeRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.RealtimeServices.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.TransactionService.CouponTransactionServiceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)
**Inherits:** RealtimeRequest

| Type | Property |
|------|----------|
| `IEnumerable<string>` | CouponCodeIds |
| `string` | CustomerAccount |
| `long` | ChannelId |
| `string` | TransactionId |
| `string` | SalesId |

### ValidateDiscountsServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateDiscountsServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.PricingService (Microsoft.Dynamics.Commerce.Runtime.Services.Pricing.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `SalesTransaction` | Transaction |
| `Cart` | Cart |

### ValidateWarrantyPriceApplicabilityServiceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateWarrantyPriceApplicabilityServiceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll
**Handled by:** Microsoft.Dynamics.Commerce.Runtime.Services.WarrantyService (Microsoft.Dynamics.Commerce.Runtime.Services.Merchandising.dll)
**Inherits:** ServiceRequest

| Type | Property |
|------|----------|
| `Warranty` | Warranty |
| `ProductPrice` | WarrantableProductPrice |
