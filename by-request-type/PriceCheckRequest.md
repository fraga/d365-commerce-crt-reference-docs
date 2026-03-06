# PriceCheckRequest

**Full name:** `Microsoft.Dynamics.Commerce.Runtime.Messages.PriceCheckRequest`
**Assembly:** Microsoft.Dynamics.Commerce.Runtime.Messages.dll
**Domain:** pricing
**Inherits:** Request

## Handled By

- [Microsoft.Dynamics.Commerce.Runtime.Workflow.PriceCheckRequestHandler (Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)](../by-handler/Microsoft.Dynamics.Commerce.Runtime.Workflow.PriceCheckRequestHandler.md)

## Properties

| Type | Name |
|------|------|
| `string` | ItemId |
| `string` | InventoryDimensionId |
| `string` | UnitOfMeasureSymbol |
| `string` | CustomerAccountNumber |
| `decimal` | Quantity |
| `string` | Barcode |
| `long` | CatalogId |
| `string` | LoyaltyCardId |
| `IEnumerable<AffiliationLoyaltyTier>` | AffiliationLoyaltyTiers |
