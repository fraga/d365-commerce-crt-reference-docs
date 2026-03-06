# GetProductPriceRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductPriceRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** pricing
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.GetProductPriceRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.GetProductPriceRequestHandler.md)

## Properties

| Type | Name |
|------|------|
| `long` | ProductId |
| `string` | CustomerAccountNumber |
| `string` | UnitOfMeasureSymbol |
| `string` | LoyaltyCardId |
| `IEnumerable<AffiliationLoyaltyTier>` | AffiliationLoyaltyTiers |
