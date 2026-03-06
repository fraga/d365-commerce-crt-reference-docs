# GetActiveProductPriceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetActiveProductPriceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** pricing
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetActiveProductPriceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetActiveProductPriceRequestHandler.md)

## Triggers

- Microsoft.Dynamics.Commerce.Runtime.Workflow.ValidateBusinessPartnerCatalogTrigger (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Properties

| Type | Name |
|------|------|
| `IEnumerable<long>` | ProductIds |
| `string` | CustomerAccountNumber |
| `DateTimeOffset` | DateWhenActive |
| `ProjectionDomain` | Context |
| `IEnumerable<AffiliationLoyaltyTier>` | AffiliationLoyaltyTiers |
| `bool` | IncludeSimpleDiscountsInContextualPrice |
| `bool` | IncludeVariantPriceRange |
| `bool` | IncludeAttainablePricesAndDiscounts |
| `PriceLookupContext` | PriceLookupContext |
